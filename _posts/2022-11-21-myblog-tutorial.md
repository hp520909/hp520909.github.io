---
layout: post
title:  "安卓apk签名"
categories: 其他
tags:  其他
author: ShmilyKK
---

* content
{:toc}

1.设置Keytool到系统Path环境变量

2.使用apksigner进行签名，例如：apksigner sign --ks xxx/debug.keystore --ks-key-alias xxx xxx/xxx.apk

3.使用新签名的文件进行发布
