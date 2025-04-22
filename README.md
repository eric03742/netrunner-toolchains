# netrunner-toolchains

*《矩阵潜袭》中文卡牌数据库工具链介绍*

## 简介

在开发诸如QQ群卡查机器人、微信卡查小程序等项目的过程中，为准备与处理数据，我们开发了一系列开源库与工具。本仓库以README文档的形式整理收录了这些项目。

## netrunner-card-text-Chinese

*《矩阵潜袭》卡牌中文文本数据*

**项目地址**：[eric03742/netrunner-card-text-Chinese](https://github.com/eric03742/netrunner-card-text-Chinese)

以CSV格式存放矩阵潜袭中所有卡牌的中文文本，并通过Git Action同步文本调整更新。

## netrunner-entities

*《矩阵潜袭》中文卡牌数据库实体定义*

**项目地址**：[eric03742/netrunner-entities](https://github.com/eric03742/netrunner-entities)

使用 [TypeORM](https://typeorm.io/) 定义《矩阵潜袭》中文卡牌数据库中所使用的表结构，作为需要访问《矩阵潜袭》中文卡牌数据库的项目的DAO实现。

## netrunner-database

*《矩阵潜袭》中文卡牌数据库导入工具*

**项目地址**：[eric03742/netrunner-database](https://github.com/eric03742/netrunner-database)

根据 [NetrunnerDB](https://netrunnerdb.com/)、[jinteki.net](https://www.jinteki.net/) 等网站的公开API数据生成/更新中文卡牌数据库中的数据。

## netrunner-card-data

*《矩阵潜袭》中文卡牌数据库导出工具*

**项目地址**：[eric03742/netrunner-card-data](https://github.com/eric03742/netrunner-card-data)

将中文卡牌数据库中的数据导出为JSON格式的文本文件。

## netrunner-card-scans

*《矩阵潜袭》卡牌图片资源下载工具*

**项目地址**：[eric03742/netrunner-card-scans](https://github.com/eric03742/netrunner-card-scans)
将 [NetrunnerDB](https://netrunnerdb.com/) 上的卡图下载至本地。

## 作者

[Eric03742](https://github.com/eric03742)
