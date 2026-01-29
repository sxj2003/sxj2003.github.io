---
title: "Vakaros使用教程"
date: 2026-01-29
draft: false
tags: []
author: "Sun Xiujie"
description: ""
showToc: true
TocOpen: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowWordCount: true
---

本文记录使用水上仪器 atlas2 的使用过程，供参考。

## 前提

HarmonyOS无适配vakaros connect软件，需要ios或android系统。

笔者所用**m78星云**vpn下载在ios设备上，需要非大陆apple ID，过于麻烦，最终转向了android设备。

## Atlas2 UI与功能解析

### 主页面

1. 设备身份：品牌与型号、版权声明copyright；
2. 配置说明：（布局、功能集）配置方案、功能权限（是否均已开启）、赛事级别class；
3. 系统状态：固件版本、序列号、全球定位系统版本；
4. 连接用QR code。

<img src="/image/vakaros1/image.png" alt="主页面" style="width: 50%; display: block; margin: 0 auto;">

### 主要航行屏幕

> 四周含时间、电量、按钮含义提示

1. 自定义：

   - 界面调整

     - 2、3、4块及位置的调整
     - 内容调整：包括COG\HDG\SOG\DETL\TTL\TTB\TIMER\VMG(大组件与小组件版本)，小组件另有Orientation

   - 按钮调整

     - 线、角度、重置、开始、+1的组合

   - LED灯

     - DTL、TTB、HA等，主要将led作为数据大小的可视化或者进度条，亮度可设置。

     <img src="/image/vakaros1/led配置.png" alt="led配置页面" style="width: 50%; display: block; margin: 0 auto;">

2. Pre-Made

   - 启航阶段

     - 图形化启航：顶部是倒计时，中间是起航线示意图（含40m、80m线，可设置），底部其他指标（KTS\HDG\DTL\TTL）
     - 数字化启航：纯粹数字排列，含倒计时、HDG、KTS、DTL

   - 比赛阶段

     - 三个角度与速度
     - heading（可选含shift tracking视图或avg视图）与速度
     - 最大速度视图（10s窗口max与max）

   > heading shift tracking视图用来追踪风向的变化

## 日志数据存放

1. 在atlas中
2. 在app中
3. 导出本地
4. 开放给第三方软件

## Atlas2 其他设置

### 背光

可设置自动背光显示（有亮度与灵敏度自定义），照亮暗光下的屏幕显示、按钮、led灯

### 声音

配备扬声器，可设置声音大小

### 测量参数设置

HDG\SOG\COG\HEEL\TRIM\VMG可设置单位、阻尼、窗口大小

### 方向设置

根据平放或直立矫正安装偏移

### 添加合作的第三方传感器

如风速仪、水流仪、水深仪等

---

**详细见[官网说明书](https://support.vakaros.com/)**
