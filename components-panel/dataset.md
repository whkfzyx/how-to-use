# 数据集

----

## 简介

### 功能

请求和承载数据，监听查询事件，当对应的查询事件被触发后，会在请求数据时加上查询参数。

### 应用场景

单独使用没有意义，需要结合展示组件一同使用

### 缩略图

![MacDown Screenshot](images/dataset.png)

![MacDown Screenshot](images/dataset1.png)

### 组件依赖

依赖于展示组件

## 配置说明

|配置项|必填|示意图|格式|版本|
|:--|:--|:--|:--|:--|
|查询API|是|![MacDown Screenshot](images/dataset-api.png)|/xx/xx or  http://xxx/xx/xx or https://xxx/xx/xx|v0.0.1|
|默认参数|否|![MacDown Screenshot](images/dataset-mrcs.png)|{"getdate":"new Date()"}|v0.0.1|

## 注意事项

API规范

数据格式规范