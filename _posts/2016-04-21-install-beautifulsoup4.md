---
layout: post
title:  "python 安装第三方插件beautifulsoup4"
date:   2016-04-21 16:13:19 +0800
categories: jekyll update
---
# python: pip install 命令失效 #
​    在学习视频中，需要安装`python`第三方库`beautifulsoup4`，使用`pip install beautifulsoup4`命令报错，内容如下：

``` Fatal error in launcher: Unable to create process using ```

​    查了某些博客内容，好像是说明`pip`需要更新，我用了推荐的`python -m pip install -U pip`更新完毕后再继续使用`python -m pip install beautifulsoup4`，这时的确可以运行起来，但是会报找不到版本，头疼中.......因为个人觉得版本错误是不可能有问题的，于是又试了各种方法都不见效果。最后果断手动安装`beautifulsoup4`的压缩包，直接解压后到该解压包的根目录下，控制台输入`python setup.py install`，然后可行了.......
​    三个小时的安装过程的确可以，时间是什么，让其在这里发生。
