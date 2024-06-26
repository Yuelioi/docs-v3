---
title: HDR 压缩扩展器
order: 6
---

# HDR Compander - HDR 压缩扩展器

## 简述

来自[官方文档](https://helpx.adobe.com/cn/after-effects/using/utility-effects.html)
太遥远，日后校正

“HDR 压缩扩展器”（压缩程序/扩展器）效果使您能够使用不支持高动态范围颜色（例如 8-bpc 和 16-bpc
效果）的工具，而不必牺牲素材的高动态范围。

“HDR 压缩扩展器”效果的工作方式是，首先压缩 HDR 图像中的高光值以便它们归入 8-bpc 或
16-bpc（低动态范围）图像的范围内，然后将这些值重新扩展为 32-bpc 范围。

在效果堆栈中将“HDR 压缩扩展器”效果应用于低动态范围效果上方的图层一次，并应用于低动态范围效果下面的图层一次。

因为“HDR 压缩扩展器”效果的第一个实例通过采样来压缩值范围，所以会损失一些精度。因此，仅当您接受为了高动态范围而损失值的一些精度时，才应使用“HDR
压缩扩展器”效果。

此效果适用于 8-bpc、16-bpc 和 32-bpc 颜色。

**注意**

使用“HDR 压缩扩展器”效果的一种更方便的方法是应用“压缩扩展动态范围”动画预设。此动画预设包括一个表达式和“HDR
压缩扩展器”效果的两个实例：第一个实例选择了“压缩范围”，第二个实例选择了“扩展范围”。表达式自动将第二个实例的“增益”和“灰度系数”设置为与您为第一个实例设置的相同。在“HDR
压缩扩展器”效果的这两个实例之间插入您选择的任何低动态范围效果。

## 效果展示

## 教程

## 中英日对照

![](https://mir.yuelili.com/user/AE/effects/AE-Effects-Utility-HDR_Compander.png)![](https://mir.yuelili.com/user/AE/effects/AE-Effects-Utility-HDR_Compander_cn.png)

| Mode  | 模式     | モード | Compress Range | 压缩范围 |     |
| ----- | -------- | ------ | -------------- | -------- | --- |
|       |          |        | Expand Range   | 扩展范围 |     |
| Gain  | 增益     | ゲイン |                |          |     |
| Gamma | 灰度系数 | ガンマ |                |          |     |

## 参数详解

### 应用“HDR 压缩扩展器”效果

- 将“HDR 压缩扩展器”效果应用于 32-bpc 项目中的图层。

- 为“模式”选择“压缩范围”。

- 将“增益”设置为要在压缩范围中表示的最大值，即，图像中的最高白色值。不要将“增益”设置得太高；您用于高亮的 16-bpc 值越大，中间调（绝大多数像素）的压缩程度就越大，而此过程中丢失的数据也就越多。

- 设置“灰度系数”。灰度系数影响范围中值的分布，从而可提高范围中特定区域的精度。

- 向图层应用您选择的任何低动态范围效果。

- 向图层应用“HDR 压缩扩展器”效果的另一个实例。确保“HDR 压缩扩展器”的第二实例排在您已应用的任何 8-bpc 或 16-bpc 效果之后（下面）。

- 为“HDR 压缩扩展器”效果的第二个实例的“模式”选择“扩展范围”。

- 将“增益”和“灰度系数”设置为与“HDR 压缩扩展器”效果的第一个实例中相同的值。
