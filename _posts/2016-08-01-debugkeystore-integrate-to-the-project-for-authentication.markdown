---
layout: post
title:  今日修改：debug.keystore集成到了项目中，使得在所有环境下都能访问Firebase auth
date:   2016-08-01 21:50:00 +0800
categories: app update
---

Firebase auth用于用户登录验证时，需要提供签名key的sha1。
在开发过程中，我们采用Android studio为每个项目自动生成的[debug.keystore](https://developers.google.com/android/guides/client-auth)

为了保证每台不同主机都能用一个key。把debug.keystore放到了项目中。并且在app中增加了signing.properties文件，说明key的密码，在app/build.gradle中进行读取。

目前不知道把debug.keystore放到项目中是否安全。

下载源码说明:
https://docs.google.com/document/d/1RABC8NaBwPHCKUnoxYupXJXutGs1KZNIqk_-q0nRgqk/edit

XH
