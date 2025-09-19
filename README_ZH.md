 <h1 align="center">CouchDB数据库</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[CouchDB](https://github.com/apache/couchdb) 是一款由 Apache 软件基金会维护的 开源分布式文档数据库，基于 NoSQL（非关系型） 架构设计，核心特点是 高可用性、高容错性和灵活的数据模型，尤其适合需要分布式存储和离线数据同步的场景。本商品基于鲲鹏服务器的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的CouchDB。

## 核心特性

- **‌数据模型‌：** 以 JSON 文档为存储单元，支持灵活的无模式结构，单个文档可包含复杂嵌套数据。
- **分布式架构‌：** 支持多节点数据同步与容错，通过 Erlang实现高并发处理和故障隔离。
- **MVCC‌：** 每个文档版本独立存储，确保并发操作时数据一致性，旧版本保留直至被明确删除。
- **RESTful API‌：** 基于HTTP接口，支持多种编程语言（如 JavaScript、Python、Java）。

本项目提供的开源镜像商品 [**CouchDB数据库**]() 已预先安装3.5.0版本的CouchDB及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                      | 特性说明 | 备注 |
|-----------------------------------------------------------------------------------------------------------| --- | --- |
| [CouchDB-3.5.0-kunpeng](https://github.com/HuaweiCloudDeveloper/couchDB-image/tree/CouchDB-3.5.0-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/couchDB-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md