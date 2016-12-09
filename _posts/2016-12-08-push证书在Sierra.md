---
layout:     post
title:      "push"
subtitle:   "push"
date:       2016-12-08
author:     "未久夕多"
header-img: "img/home-bg-o.jpg"
tags:
    - 
    - Sierra
---

> 在mac Sierra  10.12.1 版本中 发现测试的push一直调不好。报证书错误。但是同样的代码和证书在其他人电脑上是好的。唯一的区别就是别人的电脑版本是10.11.6 Orz。。。

### 解决方法
* [APNs push notification with macOS Sierra](http://stackoverflow.com/questions/39612022/apns-push-notification-with-macos-sierra)
* sudo mv cacert.pem /usr/local/libressl/etc/ssl/cert.pem