﻿=== WP Dialog ===
Contributors: ZhangGe
Donate link: https://zhang.ge/about.html
Tags: WP_Dialog,artdialog,blog dialog,友好对话框,博客对话框,搜索来路,随机滚动条,底部滚动条,scroll bar
Requires at least: 3.0
Tested up to: 5.2.2
Stable tag: 1.2.5.5
License: GPLv2 or later
License URI: https://zhang.ge/4718.html

The Friendly Dialog And Rand Scroll Bar Wordpress Plugin. WordPress友好对话框&随机滚动条插件

== Description ==

Added a Friendly Dialog And Rand Scroll Bar for Wordpress blog that for display some Friendly Dialog at sometimes.

为你的博客添加一个友好对话框功能。

插件特色    
    1、能够取得访客搜索来路和搜索关键词，并在右下角滑出欢迎对话框；    
    2、能够区分用户是否在博客留过言，从而给出自定义欢迎提示；
    3、在博客底部集成随机文章滚动推荐条，并在右侧集成手动呼出对话框和嗨一下按钮；
    4、当有人复制博客任何内容时，将弹出友好的版权保留提醒；
    5、给WordPress集成Cookies记录评论者信息功能，不受缓存影响。 
        
制作这个插件的初衷是为了努力增加网站粘性！尽最大的可能留住通过搜索引擎过来的用户，因为虽然博客可能无法满足用户的搜索需求，但并不是博主不会，只是博客未写到这方面的内容。所以，我希望通过这样一个友好对话，能让用户主动留言联系博主，让博主及时扩充用户所需内容，在丰富博客的同时提高用户粘性，最终降低跳出率！当然，后来还加上了复制提醒功能，主要发现很多人偷摸转载却忘记保留原文链接，所以插件也就温馨的提示一下，防君子不防小人，希望你喜欢！

详情请浏览：[http://zhang.ge/4718.html](http://zhang.ge/4718.html)

== Installation ==

可以通过以下两种方法的其中一种来安装 WP-Dialog 插件：

1. 将下载的文件解压缩，然后将`WP-Dialog`文件夹 上传到 `/wp-content/plugins/`目录，在插件后台启用即可

2. 直接在后台-安装插件，搜索'WP-Dialog'，按照提示安装启用

== Frequently Asked Questions ==

如果发现启用插件后，无法弹出对话框，可能有如下情况：

1. 极个别的强迫症优化插件会禁止js输出，导致无法弹出，那没办法，鱼和熊掌不可兼得也;

2. 博客可能存在缓存，导致js并未及时加载，清楚缓存再试;

3. 其他未知冲突，请到插件主页留言[http://zhang.ge/4718.html](http://zhang.ge/4718.html)

若发现滚动条无法滚动，可能的情况有：

1. 博客未正确加载JQuery或重复加载导致冲突，解决办法参考[http://zhang.ge/4387.html](http://zhang.ge/4387.html)

Best Regards！

== Screenshots ==

1. olduser Screenshot

2. newuser Screenshot 

3. searcher Screenshot

4. scroll Screenshot
 
== Changelog ==
= 1.2.5.5 =

* 修复Cookie写入失败的BUG

= 1.2.5.4 =

* 修复版权提醒无法关闭问题

= 1.2.5.3 =

* 修复一个可能与滑动解锁冲突的问题


= 1.2.5.2 =

* 新增好搜、必应、神马和有道搜索来路判断功能；
* 压缩js代码，优化加载速度；
* 对话框改为在移动端不弹出。

= 1.2.5.1 =

* 修复导致部分主题某些元素意外隐藏问题；
* 修复部分对话框相关图片404问题。

= 1.2.5 =

* 修复在部分主题下滚动条不显示文字或错乱问题；
* 修复底部滚动文字在宽度变窄时会消失的问题；
* 修改为当宽度小于480px底部滚动条自动隐藏；
* 新增宽度小于720px时，不会自动弹出欢迎框；
* 新增cookies记忆评论者信息功能，可在后台关闭；
* 其他未及时记录在案的CSS冲突修正。

= 1.2.4.4 =

* 修复了在IE下复制文字无法弹出版权提醒的BUG；
* 新增宽度小于900px时隐藏底部公告栏的特性。

= 1.2.4.3 =

* 修复在部分主题（比如大前端的主题：DUX,XIU等）下CSS冲突导致元素不显示的BUG

= 1.2.4.2 =

* 修复了搜索引擎来路显示空白的BUG

= 1.2.4.1 =

* 修复了导致WordPress前台工具条消失的BUG
* 修复了可能导致用户名乱码的BUG

= 1.2.4 =

* 后台新增欢迎内容设置，可自定义对话框欢迎文字内容，并支持HTML语言

= 1.2.3 =

* 新增网页嗨一下功能，首次启动请到插件设置界面填写歌曲url地址
* 后台新增邮件订阅设置，可自定义滚动条右侧的博客订阅按钮地址
* 后台新增留言地址设置，让对话框中显示留言板超链接
* 修复可能从cookie获取用户名乱码的问题

= 1.2.2 =

* 插件设置新增主题对话框功能开关

= 1.2.1 =

* 修复关闭滚动条导致版权提醒功能失效的bug

= 1.2.0 =

* 新增插件设置功能

= 1.1.0 =

* 新增底部滚动条功能

= 1.0.0 =

* 发布WP-Dialog 插件

== Upgrade notice ==

* 插件首次发布，有任何问题请至插件主页反馈，非常感谢！

== Arbitrary section 1 ==
