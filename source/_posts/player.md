---
title: 视频插入测试
date: 2018-04-07 08:33:20
tags:
categories: Test
thumbnail: /img/Office.jpg
---

## 测试视频插入

> &emsp;&emsp;本文测试国内主流网站的视频插入。
>
> &emsp;&emsp;尝试主流视频网站，**bilibili和优酷的插入效果最好**。当然，Youtube肯定是最好的，但是可能访问。
>
> &emsp;&emsp;爱奇艺和腾讯视频会自动播放很烦人啊！





### 1. 优酷

> &emsp;&emsp;可选清晰度，不会跳转到原网站播放。
>
> &emsp;&emsp;插入需要在Markdown添加“\<center\>”标签，分享代码嵌入其中。需要自行添加宽高信息：height=600 width=80% 

<center><iframe height=600 width=80% src='http://player.youku.com/embed/XMzQxODA3NDI0NA==' frameborder=0 allowfullscreen='true'></iframe></center>



### 2. B站

> &emsp;&emsp;目前看来只能插入360P，切换清晰度会跳转到B站播放。插入的视频可全屏播放。
>
> &emsp;&emsp;插入需要在Markdown添加“\<center\>”标签，分享代码嵌入其中。需要自行添加宽高信息：height=600 width=80% 

<center><iframe height=600 width=80% src="//player.bilibili.com/player.html?aid=8824952&cid=14558275&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe></center>



### 3. 爱奇艺

> &emsp;&emsp;需要flash才能播放。
>
> &emsp;&emsp;插入需要在Markdown添加“\<center\>”标签，分享代码嵌入其中。建议修改高度为600， 宽度为80%。没找到禁止自动播放的方法，只给个例子了。

```html
<center><iframe src="http://open.iqiyi.com/developer/player_js/coopPlayerIndex.html?vid=454e9803e3f7961c40da5de8b91f16ca&tvId=7550472909&accessToken=2.f22860a2479ad60d8da7697274de9346&appKey=3955c3425820435e86d0f4cdfe56f5e7&appId=1368&height=100%&width=100%" frameborder="0" allowfullscreen="true" width="80%" height=600></iframe></center>
```



### 4. 腾讯视频



>&emsp;&emsp;基本只能内嵌整个网页，也需要自己添加center和宽高信息。没找到禁止自动播放的方法，只给个例子了。



```html
<center><iframe  src="https://v.qq.com/x/page/t0530b5afef.html" width=80% height=600 autoplay=false></iframe></center>
```





