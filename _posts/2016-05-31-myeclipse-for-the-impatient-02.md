---
layout: post
title: myeclipse插件link安装 
date: 2016-05-31 15:14:00
category: "myeclipse"
---

myeclipse插件有多种安装方式.本人倾向于link安装.

- myeclipse andriod安装

	1. 下载android SDK.
	2. 下载android ADT,解压将plugins文件夹和features文件夹到E:\MyEclipse\link\adt下.
	3. 在MyEclipse安装文件夹的dropins子文件夹中，建立一个adt.link文件,里面写入adt插件解压的地址，本文中adt.link文件里面内容为：path=E:\\\\MyEclipse\\link\\adt
	4. 打开MyEclipse，会发现ADT插件已经安装上了.选择android SDK 路径,按照提示下载更新即可，Google官网上面的资源需要翻墙才行.

- 以上即为android ADT插件的安装过程，如果还是觉得麻烦，或者没能正确安装上，那么还有一个偷懒的方法，
	谷歌公司为我们提供了一个已经安装好了ADT插件的Eclipse包——ADT Bundle，只要你本地安装好了JDK环境，
	那么，只用下载这个Eclipse包，即可进行开发，这个Eclipse适合只做Android开发的用户使用，
	整体体验还不错。我们到ADT官网，点击左边菜单栏的Download，然后，点击Download the SDK ADT Bundle for Windows,
	解压下载下来的压缩包到本地文件夹，找到文件夹下eclipse文件夹下的eclipse.exe，双击运行这个，即可进入Android开发啦
