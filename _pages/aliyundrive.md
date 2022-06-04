---
layout: page
title: 阿里云盘
include_in_header: false
include_in_footer: false
locale: en
---

## 如何用Chrome浏览器获取

1. 在电脑上使用 Chrome 浏览器登录阿里云盘官网 https://www.aliyundrive.com/drive

2. 选择 Chrome 的菜单 -> 视图 -> 开发者 -> 审查元素 （或者直接在网页上右击，选择审查元素）

3. 找到 Application -> Storage -> Local Storage -> Token -> refresh_token

![](/assets/aliyundrive.png)

## 如何用手机Safari获取

1. 从AppStore下载Web Inspector并安装

2. 去系统设置- Safari 找到Web Inspector并启用，可以设置只允许一天

3. 在Safari打开网址 https://www.aliyundrive.com/drive 如果没有登录就进行登录操作

4. 点击地址栏旁边的Aa，点击Web Inspector

5. 点击弹出面板中的Resources，找到refresh_token，复制后面的那段字符串，注意不要复制引号冒号