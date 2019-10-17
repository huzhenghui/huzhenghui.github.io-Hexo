---
title: Hexo Init
comments: true
tags:
  - huzhenghui.github.io
  - hexo
categories:
  - - huzhenghui.github.io
    - operation
keywords:
  - git
  - hexo
date: 2019-10-16 13:31:58
updated: 2019-10-17 12:35:48
---

# Hexo Setup

{% post_link "Hexo-Setup" "See Hexo Setup" %}

# Hexo Init

## 进入项目目录

```bash 进入项目目录
cd huzhenghui.github.io-Hexo
```

## 本地测试

```bash 本地测试
hexo server --open --debug
```

## 初始化代码仓库

```bash 初始化代码仓库
git init
```

## 设置远程仓库

```bash 设置远程仓库 https://github.com/huzhenghui/huzhenghui.github.io-Hexo huzhenghui.github.io-Hexo
git remote add origin git@github.com:huzhenghui/huzhenghui.github.io-Hexo.git
```

## 关联代码分支

```bash 关联代码分支
git branch --set-upstream-to=origin/master master
```

## 提交代码

```bash 提交代码
git branch --set-upstream-to=origin/master master
```