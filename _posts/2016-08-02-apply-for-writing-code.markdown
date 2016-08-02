---
layout: post
title:  "小组成员申请写代码的步骤"
date:   2016-08-02 21:14:00 +0800
categories: project
---
目前代码已经托管在了Google Cloud Reporsitory中，之所以用这个平台主要是出于私有仓库的考虑。另外，能访问Google Cloud的话，也就能访问Firebase，我们的项目后端是使用Firebase的。

为了保证公平性，小组成员在编码阶段参与才能算是团队的一份子。

申请步骤：

1）在[设计文档](https://docs.google.com/document/d/173q5tWVMB-MY9Y4Gq3zGYhkAAo8CAnrdaRJYUe9B9hk/edit)中的相关页面签上自己的名字，作为相关页面的负责人。

2）把Gmail账户发给我，便于发送访问私有仓库的邀请。

编码准备工作：

1）确保能使用Google Cloud Console，配置过程参见[这篇文档](https://docs.google.com/document/d/1RABC8NaBwPHCKUnoxYupXJXutGs1KZNIqk_-q0nRgqk/edit?usp=sharing)

2）快速学习[Material Design](https://codelabs.developers.google.com/codelabs/material-design-style/index.html)和[Firebase](https://codelabs.developers.google.com/codelabs/firebase-android/index.html)的codelab

3) 为Android Studio安装好最新的Google Play services和模拟器

目前开发团队里面有TQ和我。欢迎大家踊跃报名。

{% highlight cpp %}
#include<iostream>
using namespace std;

int main(){
    string answer;
    cout<<"你真的准备好了做出一款有益的好用的APP了吗？"<<endl;
    cin>>answer;
    if(answer == "是的"){
        cout<<"欢迎! 请仔细阅读上面的条款。相信开发这款app会是一个有趣的过程。"
    }else{
        cout<<"感谢关注！我们会在网站持续更新项目进度。"
    }
    return 0;
}
{% endhighlight %}


XH

2016年8月2日


