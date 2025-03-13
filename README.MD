# 微信公众号二维码页面

## 简介

这是一个简洁的微信公众号二维码页面，用户可以通过扫描二维码关注你的公众号。该页面还支持通过 URL 参数实现返回功能，方便在任何页面上使用。

## 使用方法


```
目录结构
.
├─ image
│  ├─ qrcode.png
│  └─ logo.png
└─ index.html
```

### [直接打开效果(点击预览)](https://blog.zhuns.top/wxz/index.html)

直接打开就是一个二维码的界面

```
https://blog.zhuns.top/wxz/index.html
```
![](/img/01.png)

### [携带参数后打开效果(点击预览)](https://blog.zhuns.top/wxz/index.html?redirectTo=https://github.com/zhunse/wxm)

会多出一个 ```返回页面``` 的按钮，点击后即可跳转到 ```?redirectTo=``` 参数后面的链接

```
https://blog.zhuns.top/wxz/index.html?redirectTo=https://github.com/zhunse/wxm
```
![](/img/02.png)