---
title: "如何用hugo搭建博客"
date: 2020-03-31T21:18:39+08:00
draft: false
---

# 如何用hugo搭建博客
## 这里讲的是window系统的搭建方法
### 一、安装hugo
1、下载hugo安装包，把解压后的路径放进PATH

2、之后重启终端，运行hugo --version 查看版本
### 二、快速搭建博客
1、进入Hugo官网，点击quick start快速开始

2、从Step2开始抄代码一直到Step7

3、得到public目录，这就是我们的博客站点。public目录就是一个网站

4、hugo server -D 可以预览草稿

5、hugo server 可以预览非草稿
### 三、创建一个github repo
仓库名为 你的github用户名.github.io
### 四、又一次创建本地仓库
1、进入public
2、git init
3、git add
4、git commit
### 五、关联远程仓库
1、git remote add origin
git@github.com:xxxx/x.github.io.git
2、必须是git开头
3、git push
### 六、打开x.github.io的GitHub Page
 





