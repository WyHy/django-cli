# django-cli
基于django的后端开发脚手架

## 内容列表

- [背景](#背景)
- [维护者](#维护者)
- [编码原则](#编码原则)
- [文件布局](#文件布局)
- [项目架构](#项目架构)
- [数据库设计](#数据库设计)
- [业务流程设计](#业务流程设计)
- [如何测试](#如何测试)


## 背景

方便项目开发初始化

## 维护者

[@wangy](https://github.com/WyHy)

## 编码原则

1. 模块文件请存放于 modules 文件夹
2. 每个模块一个 .py 文件
3. 每个 .py 文件中的函数请使用[@浅函数](https://tech.meituan.com/2019/09/19/common-method-of-reduce-complexity.html)模式

## 文件布局

- docs : 项目文档
- Mongo : mongoDB配置
- Postgres : PostgrSQL配置
- Redis : Redise配置
- src : 项目代码
- docker-compose-dev.yaml : dev环境docker-compose 配置项
- docker-compose-release.yaml : release环境docker-compose 配置项
- Makefile : Makefile

## 项目架构

## 数据库设计

## 业务流程设计

## 如何测试
