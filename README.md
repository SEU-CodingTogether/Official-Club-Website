# 俱乐部官方网站

## 说明

本教程为网站维护人员编写。

## 安装nodejs和hexo

首先，根据[这个网站](https://hexo.io/zh-cn/docs/index.html#%E5%AE%89%E8%A3%85)安装nodejs和hexo.

## 添加文章

```
hexo new 文件名
```

这会在source/_post目录下创建一个“文件名.md”文件。默认front-matter内容如下：

```
title: {{ title }}
date: {{ date }}
tags:
categories: #分类
thumbnail: #封面图片 /img/图片名

```

- title是文章名，注意不要用中文开头
- date是时间，自动生成无需修改
- tag无需修改
- categories:分类，填写一个分类
- thumbnail： 封面图片，保存在“source/img目录”

## 编程挑战的日常

直接修改“source/about”目录下index.md文件即可。

## 维护团队成员

直接修改“source/_data”目录下links.yms文件即可。

```
名称 :
      link: 点击连接地址   
      avatar: 头像地址
      descr: 描述
```

## 社团剪影

直接修改“source/_data”目录下gallery.yms文件即可。

```
图片名称1:
  full_link: 图片地址
  thumb_link: 略缩图地址
  descr: 图片描述
```

## 关于我们

直接修改“source/contact”目录下index.md文件即可。



## 部署

```
sudo rm -r .deploy_git
hexo clean
hexo deploy

```



## 更多定制

本项目使用了hexo的miccall主题，更多定制修改参见[https://github.com/miccall/hexo-theme-Mic_Theme](https://github.com/miccall/hexo-theme-Mic_Theme).

