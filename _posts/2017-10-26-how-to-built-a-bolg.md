---
layout: post
title: 如何搭建一个博客
date: 2017-10-26
categories: blog
tags: [总结,知识管理]
description:这是我写的第一篇博客
---


###说在前面的话

>当我加入HICA这个大家庭的时候
我还没想过会在这里获得怎样的惊喜
一路过来就是走一步看一步
来到hica，再加入hica的网络组，认识这么多志同道合的小伙伴和热情睿智成熟稳重的学长学姐们。
还学了很多从未接触过的技能。
这篇博客是我在hica网络组的第二次作业，即写一篇博客阐述我是如何搭建一个属于自己的博客的。
而第一个作业就是搭建自己的博客。

###进入正题
*那么我到底是怎样搭建一个属于自己的博客的呢？*
*首先我们在第一次培训之前，网络组的学姐在QQ群里发了一个公告，内部附有一个网址，让我们自己预习。里面非常详细专业，的确对于完全是初学者的我是个极大的挑战，但的确帮助很大，附上这个有用的链接，感兴趣的小伙伴可以看一看。*

[如何利用GitHub搭建一个独立博客](http://www.cnfeat.com/blog/2014/05/10/how-to-build-a-blog/)

*其中所说的第一步，即在godaddy上购买一个域名，大部分小伙伴都没做到，因为校网不是特别的善解人意，也0因为价格相对于我们大部分学生阶层来说不是很好接受。所以这一步我也直接跳过了，接下来是依次下载两个软件*

> - [Node.js](https://nodejs.org/en/)  
>- [git](https://git-scm.com/)

*下载完成并且注册完你的GitHub账号之后打开Github bush 然后按照教程中写的一步一步敲入代码，配置自己的SSH Keys*
>  **$ ssh-keygen -t rsa -C "邮件地址@youremail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/your_user_directory/.ssh/id_rsa):<回车就好>**
- 注意 1: 此处的邮箱地址，你可以输入自己的邮箱地址；
- 注意2: 此处的「-C」的是大写的「C」

*然后系统会要求你输入密码*
> **Enter passphrase (empty for no passphrase):<输入加密串>
Enter same passphrase again:<再次输入加密串>**

*在回车中会提示你输入一个密码，这个密码会在你提交项目时使用，如果为空的话提交项目时则不用输入。这个设置是防止别人往你的项目里提交内容。
注意：输入密码的时候没有 * 字样的，你直接输入就可以了。
最后看到这样的界面，就成功设置ssh key了*




![](http://upload-images.jianshu.io/upload_images/32598-cf2af2bff37b1031.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###添加SSH Keys到GitHub
*在本机设置 SSH Key 之后，需要添加到 GitHub上，以完成 SSH 链接的设置。
1、打开本地 id_rsa.pub 文件（ 参考地址 C:\Documents and Settings\Administrator.ssh\id_rsa.pub）。此文件里面内容为刚才生成的密钥。如果看不到这个文件，你需要设置显示隐藏文件。准确的复制这个文件的内容，才能保证设置的成功。
2、登陆 GitHub 系统。点击右上角的 Account Settings--->SSH Public keys ---> add another public keys
3、把你本地生成的密钥复制到里面（ key 文本框中）， 点击 add key 就ok了*

![](http://upload-images.jianshu.io/upload_images/32598-c8b55d62cc0dbd07.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




然后在进行一系列小操作，完善信息啥的
我就有了一个自己的仓库
第二节课我们又学了如何简单的操作Markdown写博客
接下来就有了这篇你看看到的博客

心里有点小小的成就感。














