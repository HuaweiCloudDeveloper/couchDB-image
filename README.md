 <h1 align="center">CouchDB Database</h1>
  <p align="center">
    <strong>English</strong> | <a href="README.md"><strong>简体中文</strong></a>
  </p>


## Table of Contents

- [Repository Introduction](#repository-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction

[CouchDB](https://github.com/apache/couchdb) is an open-source distributed document database maintained by the Apache Software Foundation. It is designed based on the NoSQL (non-relational) architecture, with core features of high availability, high fault tolerance, and a flexible data model. It is particularly suitable for scenarios requiring distributed storage and offline data synchronization. This product provides out-of-the-box CouchDB based on the Huawei Cloud EulerOS 2.0 64-bit system on Kunpeng servers.

## Core Features

- **Data Model**: Uses JSON documents as storage units, supporting a flexible schema-less structure. A single document can contain complex nested data.
- **Distributed Architecture**: Supports multi-node data synchronization and fault tolerance, achieving high concurrency processing and fault isolation through Erlang.
- **MVCC**: Each document version is stored independently, ensuring data consistency during concurrent operations. Old versions are retained until explicitly deleted.
- **RESTful API**: Based on HTTP interfaces, supporting multiple programming languages (such as JavaScript, Python, Java).

The open-source image product [**CouchDB Database**]() provided by this project has pre-installed CouchDB version 3.5.0 and its related operating environment, and provides deployment templates. Follow the user guide to easily start an efficient "out-of-the-box" experience.


> **System Requirements:**
> - CPU: 2vCPUs or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                            | Feature Description | Remarks |
|-----------------------------------------------------------------------------------------------------------| --- | --- |
| [CouchDB-3.5.0-kunpeng](https://github.com/HuaweiCloudDeveloper/couchDB-image/tree/CouchDB-3.5.0-kunpeng) | Installed and deployed based on Kunpeng server + Huawei Cloud EulerOS 2.0 64bit |  |

## Get Help
- For more questions, you can contact us through [issue](https://github.com/HuaweiCloudDeveloper/couchDB-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace
- For other open-source images, please refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## How to Contribute
- Fork this repository and submit a pull request
- Synchronously update README.md based on your open-source image information