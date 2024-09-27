---
title: 版本命令的基本流程
---
# Git的命令流程
## 1.安装Git
通过Git的官方网站下载并安装Git。安装完成后，你可以在命令行（终端）中通过输入git --version来检查Git是否成功安装以及安装的版本。
## 2.初始化Git仓库
使用Git init 命令建一个新的git的仓库，并在里面创建一个.git存储所有数据和配置
```
git init
```
## 3. 配置Git用户信息

```
git config --global user.name "你的名字"  
git config --global user.email "你的邮箱地址"
```
## 4. 添加文件到暂存区
使用git add命令将文件添加到暂存区。你可以添加单个文件或整个目录

```
git add 文件名  
git add .  
```
## 5.提交更改到仓库
```
git commit -m "提交信息"
```
## 6.查看提交历史
```
git log
```
## 7.标签
使用git推送标签到远程仓库

```
git push -u origin "master"

```
## 8.清空
```
git clear
```
## 9。修改
用于回退版本并删除工作区和缓存区的修改
```
git reset --hard 
```