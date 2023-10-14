
这是一个参照[github上的一个项目](https://github.com/leopardpan/leopardpan.github.io)建立的网站，喜欢的可以给原作者一个star

>- 搭建引擎为`Jekyll`,`Jekyll`是一种简单的、适用于博客的、静态网站生成引擎。它使用一个模板目录作为网站布局的基础框架，支持Markdown、Textile等标记语言的解析，提供了模板、变量、插件等功能，最终生成一个完整的静态Web站点
>- `Jekyll`的相关教程:<https://jekyllrb.com/docs/>

[leopard](http://leopardpan.cn) 是一个简洁的博客模板，响应式主题， 适配了电脑、手机各种屏幕，看效果直接点击下面链接
 
 * [博客链接](http://leopardpan.cn) （部署在国内，访问更快）         
 * [Demo链接](http://leopardpan.github.io/) （部署在github page）         



### 使用手册

[Jekyll搭建个人博客](http://leopardpan.cn/2016/10/jekyll_tutorials1/)  :  使用Jekyll搭建个人博客的教程，及如何把这个博客模板修改成你自己的博客，里面也有大量的评论、Jekyll 搭建博客各种环境出现过的问题。

[HEXO搭建个人博客](http://leopardpan.cn/2015/08/HEXO%E6%90%AD%E5%BB%BA%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/) : 使用 HEXO 基于 Github Page 搭建个人博客， 教程里面累计了大量提问和评论，如果你在搭建博客时遇到问题，可以看看这个教程。 


#### 安装Jekyll

[Jekyll中文官方文档](http://jekyll.bootcss.com/) ， 如果你已经安装过了 Jekyll，可以忽略此处。

> $ gem install jekyll

#### 获取博客模板

> $ git clone https://github.com/leopardpan/leopardpan.github.io.git

或者直接[下载博客](https://github.com/leopardpan/leopardpan.github.io/archive/master.zip)   

进leopardpan.github.io/ 目录下， 开启本地服务 

> $ jekyll server

在浏览器输入 [127.0.0.1:4000](127.0.0.1:4000) ， 就可以看到博客效果了。


### 赞助

你可以通过下方二维码赞助本项目，资金将用于服务器开销以及今后的公共服务

感谢所有赞助过本项目的朋友，你们都为本项目贡献了自己的一份力量

<details>

<summary>微信二维码</summary>
<img width="300" src="http://leopardpan.github.io/images/payimg/weipayimg.jpg" alt="wechat">
</details>

<details>

<summary>支付宝二维码</summary>
<img width="300" src="http://leopardpan.github.io/images/payimg/alipayim.jpg" alt="alipay">
</details>


### 效果预览

#### 头像效果

![](http://leopardpan.github.io/images/readme/icon.gif)

如果你只想要我博客里的头像效果，你只需要拿 leopardpan.github.io/_includes/side-panel.html 文件里面 `头像效果` 和 leopardpan.github.io/css/main.css 里面最后面 `头像效果` 部分就行了。