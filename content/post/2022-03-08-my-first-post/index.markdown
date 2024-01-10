---
title: 搭建自己的博客
author: 'Huahui Ren'
date: '2022-03-13'
slug: my-first-post
categories: [技术]
tags: [blog]
subtitle: ''
summary: ''
authors: []
lastmod: '2022-03-08T23:25:11+08:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: yes
  placement: 3
projects: []
---

###  搭建自己的博客

之前自己基于另一套方法`hexo+github`搭过一个[博客](https://rusher321.github.io/2018/06/06/%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA/)，但是后续因为自己的换了电脑，当时搭建的那一套又没有自动备份，所以博客就停了。

前几天又心血来潮想搭建一个，之前一直关注谢益辉博客，知道他开发的[blogdown](https://bookdown.org/yihui/blogdown/netlify.html),参考着这个[教程](https://shilaan.rbind.io/post/building-your-website-using-r-blogdown/)很方便的搞好了这个博客。 主要是基于`Hugo+Netlify`。Hugo是基于go语言的静态网站的搭建，而Netlify是托管网站的地方。

比之前方便的地方就是可以自动部署。 

### :question:未解决的问题
1. post 下面的标签还没找到方法去除。 
2. 新建的时候会自动生成一个以时间命名的文件
3. 如何添加一个评论系统
4. 除了post如何新加页面，[类似这样](https://www.caitlincasar.com/index.html)
5. 学习如何修改academic theme
6. 预览如何设置仅前几行

### :panda_face:工作流
1. 新建：blogdown::new_post("2024Plan") or  blogdown:::new_post_addin() 
2. 预览：blogdown:::preview_site()
3. 插入图片： blogdown:::insert_image_addin()
4. 保存后+preview

### :smile:Tips
1. 在博客目录下加入featured.png，可以在主页面看到图片
2. 可以添加[emoji图标](https://blog.csdn.net/luo15242208310/article/details/114530777)


### :eyes:参考：

1. [Create your own site with blogdown in R](https://www.caitlincasar.com/post/blogdown/)
2. [手把手带你搭建个人博客](https://cosx.org/2022/03/build-blog-step-by-step/)
3. [blogdown's bookdown](https://bookdown.org/yihui/blogdown/)
4. [markdown基本语法学习和速查](https://markdown.com.cn/cheat-sheet.html#%E6%89%A9%E5%B1%95%E8%AF%AD%E6%B3%95)
5. [blogdown Insert Image addin](https://lcolladotor.github.io/2018/03/07/blogdown-insert-image-addin/)






