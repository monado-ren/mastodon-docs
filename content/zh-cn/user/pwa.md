---
title: 使用PWA版Mastodon
description: 你还可以通过PWA应用来浏览Mastodon或与Mastodon进行交互。
menu:
  docs:
    weight: 95
    parent: user
---
## 什么是PWA应用? {#whatis}

{{< figure src="/assets/Progressive_Web_Apps_Logo.svg" caption="Progressive Web App" >}}

PWA(Progressive Web App)，即渐进式Web应用，是结合了一系列现代Web技术的组合，在Web应用中实现和原生应用相近的用户体验的应用。

一个 PWA 应用首先是**一个网页**, 可以通过Web技术编写出一个网页应用。随后添加上 App Manifest 和 Service Worker 来实现 PWA 的安装和离线等功能。
相较于使用浏览器访问，PWA应用可以在主屏幕添加图标，并实现相似原生应用的体验。

- PWA可以添加至主屏幕，点击主屏幕图标可以实现启动动画以及隐藏地址栏
- PWA实现离线缓存功能，即使用户手机没有网络，依然可以使用一些离线功能
- PWA实现了消息推送
这些特性使得PWA应用更接近原生应用。

## 为什么要使用PWA版的Mastodon? {#why}

相比于安装第三方客户端，访问一个网页显然更加容易和迅速，
相比于直接在浏览器访问网页，使用接近原生应用的PWA应用显然更加优雅和舒适。

在另一方面，部分实例会对Web前端进行自定义修改以实现一些自己想要的功能。例如本站([Monado](https://monado.ren/)) 就修改了嘟文字数，新增了“仅本实例可见”与“嘟文翻译”功能等，以及一些自定义主题。这些变化只能体现在Web，无法应用在未经修改的第三方客户端。这也是我个人始终推荐用户使用PWA而非第三方客户端。

**安装PWA，操作上可以理解成“将网页书签添加到桌面”这样一个过程。**

## 在Android使用PWA应用 {#android}

一二三四五六
{{< figure src="/assets/image%20%2863%29.png" caption="Mastodon网站上的一个嘟文的永久链接" >}}

当你在跨站浏览其他由Mastodon驱动的远程站点时，点击任何一个交互按钮都会加载一个对话框，将你重定向到你的本地站点。

{{< figure src="/assets/image%20%288%29.png" caption="跨站嘟文回复对话框" >}}

## 在iOS使用PWA应用 {#ios}

一二三四五六
你可以使用你的Mastodon帐户登录到任何可以实现Mastodon API的应用程序。这些应用程序的列表可以在 [https://joinmastodon.org/apps](https://joinmastodon.org/apps) 中找到。

## 在桌面环境使用PWA应用 {#desktop}

一二三四五六