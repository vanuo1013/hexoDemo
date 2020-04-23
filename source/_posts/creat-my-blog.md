---
title: 创建属于你的个人博客
date: 2020-04-22 16:49:03
categories:
- [编码, Hexo]
---

## 开始之前

最近尝试了不少文档管理的方法和工具，始终还是觉得要有地方来记录自己的各种胡思乱想，于是有了这个博客，第一篇文就开坑记录一下这个博客的诞生过程吧~

------

## 环境配置

首先需要确保你已经有了基本的开发环境和工具，可按照如下内容确认或安装：

本博客使用的各工具版本为`Windows 10`+`Node 10.13.0`+`Npm 6.4.1`+`Hexo 4.2.0`+`Next 7.7.1`+`Git 2.20.1`。

<!-- more -->

### 安装Node

Node是一个JavaScript运行环境，安装Node会一并安装Npm依赖包管理工具，[点此跳转官网下载](https://nodejs.org/en/download/)或[点此查看安装手册](https://www.cnblogs.com/zhouyu2017/p/6485265.html)。

使用如下命令检测其版本号：

```
node --version
npm --version
```

### 安装Hexo

Hexo是一个可解析Markdown的博客框架，Npm安装完成后就可使用如下命令全局安装Hexo脚手架：

```
npm install hexo-cli -g
```

### 安装Git

Git是一个版本管理工具，后续也可以使用github-pages方便的部署静态网页，[点此跳转官网下载](https://git-scm.com/download)或[点此查看安装手册](https://www.jianshu.com/p/414ccd423efc)。

------

## 创建项目

1. 使用hexo命令创建一个初始化的hexo项目：

   ```
   hexo init 项目名
   ```

2. 进入刚刚创建的hexo项目并安装依赖包：

   ```
   npm install
   ```

3. 启动本地服务器预览博客页面：

   ```
   hexo server
   ```

4. 打开浏览器访问`http://localhost:4000`能显示如下界面，你的博客就创建成功啦~

  ![测试](/hexoDemo/images/20200422184618331.png)

------


## 编写博文

Hexo能将md文件解析为浏览器可识别的HTML、CSS和JavaScript，我们使用Markdown语法编写文章即可，[点此查看常用语法](https://www.runoob.com/markdown/md-tutorial.html)。

1. 使用hexo命令创建一个新的md文件：

   ```
   hexo new 文章名
   ```

2. 进入你的hexo项目source/_posts目录，打开刚刚创建的md文件，

------

## 插入图片

