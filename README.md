# 我是标题

## intro

学而思用户请看此公告

> [!NOTE]
>
> 目前学而思的自动刷入软件不可用（害死n个人了）
> 所以只能手动刷入

手动刷入教程如下

## 一.准备阶段

准备材料:
一台比较新的或者新的电脑
一个智商90以上的脑子
一双灵巧的手
一张会提问的嘴
一台系统版本为2.10的学而思学习机（2.10以上别想了）
准备资源:
将群公告的mtkclient可用和驱动USB_DK和联发科开发套件下载到电脑上
安装驱动

## 二.刷机

> [!CAUTION]
>
> **请严格按照以下教程操作**
>
> **砖了FLASH-BOOM不负责**

   使用mtkclient用USB数据线连接电脑（不是数据线不行）
   连接完成后打开flash工具
   点击解锁bootloader，正常情况下完成后会显示none
   退出软件，拔线，开机
   开机如果显示几行小字（大概意思为分区损坏，bootloader已解锁不可信）
   请再按一下开机键
   如果没有显示小字
   请使用群资源酷安某贼mtkclient命令行
   完成后会显示`device is aready unlock`
   使用mtkclient提取boot_a和boot_b两个分区
   在一台正常的手机上用magisk修补bin文件
   传到电脑上，用mtkclient写入boot（ab都要写）
   重启平板，如果不能重启
   就把原来的boot刷回来

## 结尾

恭喜你，看完了准备和刷机阶段群公告
收尾部分与常见问题稍后更新
