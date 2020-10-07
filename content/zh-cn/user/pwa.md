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

相比于安装第三方客户端，访问一个网页显然更加容易和迅速;  
相比于直接在浏览器访问网页，使用接近原生应用的PWA应用显然更加优雅和舒适。

在另一方面，部分实例会对Web前端进行自定义修改以实现一些自己想要的功能。例如本实例([Monado](https://monado.ren/)) 就修改了嘟文字数，新增了“仅本实例可见”与“嘟文翻译”功能等，以及一些自定义主题。  
这些变化只能体现在Web，无法应用在未经修改的第三方客户端。  
这也是为什么我个人始终推荐用户使用PWA而非第三方客户端。

**安装PWA，操作上可以理解成“将网页书签添加到桌面”这样一个过程。**

## 在Android使用PWA应用 {#android}

{{< figure src="/assets/image%20%2865%29.png" caption="Google Chrome" >}}
在此之前，请确认你已经安装了Chrome，Chrome是Android上对PWA支持最好的浏览器。你可以在[手机乐园](https://soft.shouji.com.cn/down/22435.html) 或[Play商店](https://play.google.com/store/apps/details?id=com.android.chrome) 下载安装。  
接下来，在Chrome中访问你想安装PWA应用的实例主页，打开菜单。
{{< figure src="/assets/image%20%2866%29.png" caption="选择“添加到主屏幕”" >}}
{{< figure src="/assets/image%20%2867%29.png" caption="确认“添加”" >}}
{{< figure src="/assets/image%20%2868%29.png" caption="你将会在桌面上看到Mastodon的PWA应用图标" >}}
{{< figure src="/assets/image%20%2878%29.png" >}}
*如果图标添加失败，请检查你是否给Chrome开启了"桌面快捷方式权限"。*
{{< figure src="/assets/image%20%2869%29.png" caption="PWA应用界面" >}}
启动这个PWA应用，可以看到界面和原生应用相似，没有了地址栏。

## 在iOS使用PWA应用 {#ios}

在iOS中，使用Safari即可安装PWA应用。  
在Safari中访问你想安装PWA应用的实例主页，打开“分享”菜单。
{{< figure src="/assets/image%20%2875%29.png" caption="选择“添加到主屏幕”" >}}
{{< figure src="/assets/image%20%2876%29.png" caption="确认“添加”" >}}
{{< figure src="/assets/image%20%2877%29.png" caption="你将会在桌面上看到Mastodon的PWA应用图标" >}}

## 在桌面环境使用PWA应用 {#desktop}

