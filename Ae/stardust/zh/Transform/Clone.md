---
title: 克隆 Clone
order: 1
---

# 克隆 Clone

## 克隆

创建一个新的粒子系统。与 ctrd d 有点像，不过更便于调节。

### 使用方法

将“克隆”节点连接到其他节点，这能复制一个新的粒子系统。

一般使用 Transform 来移动克隆过的分支，并重新设定发射器的种子值（random seed）。

### 参数

Delay（Seconds） 延时（秒）：延时原始粒子的系统

Shift Seed 种子变换：改变种子值

## 案例

主粒子为红色

添加扰乱场以及子粒子效果

| 只克隆子粒子系统                               | （复制完整体的子粒子）                         | 克隆子粒子 + 受扰乱场影响的主粒子              | （完全复制）                                   | 克隆子粒子 + 不受扰乱场影响的主粒子            | （复制完整体的子粒子+不受扰乱的主粒子）        |
| ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |
| ![](http://cdn.yuelili.com/202020140134-e.png) | ![](http://cdn.yuelili.com/202020140135-6.png) | ![](http://cdn.yuelili.com/202020140149-x.png) | ![](http://cdn.yuelili.com/202020140153-x.png) | ![](http://cdn.yuelili.com/202020140152-Q.png) | ![](http://cdn.yuelili.com/202020140152-P.png) |

注：为了显示方便，clone 后加了一个 transform 用于错位观看，为了截图美观性，没有截进去。
