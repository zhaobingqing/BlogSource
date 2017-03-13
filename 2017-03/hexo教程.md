---
title: Hexo博客平台搭建
front-matter:
layout: page
---
## 安装环境准备
### 1、Node.js
### 2、Git
## 正式安装Hexo
### 1、执行如下命令安装Hexo
```bash
npm install -g hexo
```
### 2、执行初始化命令
```bash
hexo init
```
### 3、生成静态页面
```bash
hexo generate（hexo g）
```
### 4、启动本地服务
```bash
hexo server (hexo s)
```
##### 至此就可以通过浏览器输入http://localhost:4000来进行访问生成的页面了！
## Hexo与GitHub关联
### 1、配置_config.yml文件
```bash
deploy:    
type: git               
repo: https://github.com/zhaobingqing/zhaobingqing.github.io.git                 
branch: master
```
### 2、上传至GitHub
```bash
hexo deploy
```
## 编写流程
在以后的使用过程中只需要项目中按照


```bash
hexo clean  
hexo g  
hexo deploy  
```


