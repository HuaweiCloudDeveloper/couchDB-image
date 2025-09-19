# Memcached部署指南

## ‌一、环境准备
### 系统配置
> -  服务器：鲲鹏服务器
> -  操作系统：Huawei Cloud EulerOS 2.0 64bit 
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GrB

## ‌二、安装部署部署

### 1.安装docker
参考：[安装Docker](https://support.huaweicloud.com/bestpractice-hce/hce_bp_0002.html)

### 2.拉取官方镜像
```bash
docker pull couchdb:latest
```

### 3.容器启动
```bash
# 创建数据持久化目录
mkdir -p /opt/couchdb/data
chmod -R 777 /opt/couchdb/data  # 赋予写入权限

# 启动容器
docker run -d \
  --name couchdb \
  -p 5984:5984 \
  -e COUCHDB_USER=admin \       # 设置管理员用户名
  -e COUCHDB_PASSWORD=123456 \ # 设置管理员密码
  -v /opt/couchdb/data:/opt/couchdb/data \
  --restart always \
  couchdb:latest
```
