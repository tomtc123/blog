---
icon: lucide/code-xml
title: TypeScript实战
date: 2026-05-23
categories:
  - 技术
  - TypeScript
---

# TypeScript

## 环境
```bash title="bash"
npm install -g typescript tsx
```

## REST
REST = 一种接口设计风格规范，全称：**Representational State Transfer** 表述性状态转移

日常口语：标准、规范、统一的前后端接口写法

### 1. 核心一句话
用HTTP 四个请求方式，对应增删改查，地址干净统一。

### 2. 4 个核心请求对应业务
* GET 查询数据（查）
* POST 新增数据（增）
* PUT 全量修改数据（改）
* DELETE 删除数据（删）

### RESTful API
遵守 REST 规则写出来的接口，就叫 RESTful 接口