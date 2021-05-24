---
title: '你好，雨果'
description: "應該相信，自己是生活的強者。---雨果"
date: 2021-05-01
toc: true
tags: ["博客"]
---
_很久以前就想要拥有一个自己的博客，得益于Verce，它现在以Hugo的方式出现在互联网。_

--- 

## 准备工作
- 与GitHub绑定的Vercel账号
- 域名
- Cloudflare代理


### 部署Hugo
从Template 中 clone项目，Template下面有Hugo模版，



在Vercel官网下点击New Project


![Vercel首页](https://img-blog.csdnimg.cn/2021052409094727.png?x-oss-process=image)
进入项目导入方式页面，选择从Template 中 clone项目，
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524091318197.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQ1NjYwNzQ3,size_16,color_FFFFFF,t_70)
在Template下面找到Hugo模版，导入Hugo项目
![Select Template](https://img-blog.csdnimg.cn/20210524091641532.png?x-oss-process=image)点击导入之后GitHub会出现相关仓库

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524092413764.png?x-oss-process=image)在Vercel面板可以绑定域名。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524092802245.png?x-oss-process=image)
### 使用

在GitHub提交后Vercel会自动部署更新。

文章是使用markdown格式，我本来是想用阿里云OSS对象来存储图片，可是域名没有备案，oss无法绑定，使用体验不是很好。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524095101949.png?x-oss-process=image)后来发现CSDN的博客支持图片导入方便，而且导出md文件后图片也能正常访问，目前就用CSDN当图床。

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021052409533592.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQ1NjYwNzQ3,size_16,color_FFFFFF,t_70)

#### 更改主题
如果想要更改主题，把想要更改的主题下载后放到themes目录下
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524093542184.png?x-oss-process=image)再将config.toml 文件中的Theme=" "换成对应的名称
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524093710543.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQ1NjYwNzQ3,size_16,color_FFFFFF,t_70)主题中会有使用帮助，查看Readme可以了解特性，我当前使用的主题[ananke](https://github.com/theNewDynamic/gohugo-theme-ananke)


界面的样式可以在这个文件夹下发现，我将social-share.html中的div注释后将主题中海外社交媒体分享隐藏。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524094257408.png?x-oss-process=image)
![社交板块](https://img-blog.csdnimg.cn/20210524094551599.png?x-oss-process=image)



### 效果

![首页截图](https://img-blog.csdnimg.cn/20210524090606946.png?x-oss-process=image)






