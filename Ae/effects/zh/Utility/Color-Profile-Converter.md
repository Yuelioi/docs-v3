---
title: 颜色配置文件转换器
order: 4
---

# Color Profile Converter - 颜色配置文件转换器

## 简述

以下来自[官方文档](https://helpx.adobe.com/cn/after-effects/using/utility-effects.html)。不熟悉颜色配置，故不做文档优化

“颜色配置文件转换器”效果通过指定输入和输出配置文件，将图层从一个颜色空间转换到另一个颜色空间。

大多数情况下，您应使用自动色彩管理功能从一个颜色空间转换到另一个颜色空间，而不是使用“颜色配置文件转换器”来手动进行转换。（请参阅[色彩管理](https://helpx.adobe.com/cn/after-effects/using/color-management.html#color_management)。）

**注意**

通常，您应使用色彩管理功能或者“颜色配置文件转换器”，而不是同时使用这两者。

您选择的配置文件将嵌入到项目中，这样即使将该项目传输到不具有相同配置文件的计算机，您仍然可以使用它们。在从一个颜色空间转换到另一个颜色空间时，您可以通过选择渲染意图来指定
After Effects 如何处理颜色转换。您还可以选择是否线性化输入或输出配置文件。

此效果适用于 8-bpc、16-bpc 和 32-bpc 颜色。

要转换图层的颜色配置文件，请从“输入配置文件”菜单中选择一个颜色配置文件。选择“项目工作空间”以使用项目设置（“文件”>“项目设置”）中指定的配置文件。要线性化输入配置文件，请选择“线性化输入配置文件”选项。然后从“输出配置文件”菜单中选择输出配置文件。要线性化输出配置文件，请选择“线性化输出配置文件”。在“意图”菜单中，选择渲染意图。

渲染意图选项确定如何调整源颜色。例如，位于目标色域中的颜色可能将保持不变，或者这些颜色可能会进行调整以便在转换到更小的目标色域时保持视觉关系的原始范围。

选择渲染意图的结果取决于图像的图形内容以及用于指定颜色空间的配置文件。一些配置文件会针对不同的渲染意图产生相同的结果。

在指定渲染意图时，您可以选择使用黑场压缩。黑场压缩可确保图像中的阴影详细信息通过模拟输出设备的完整动态范围得以保留。

## 效果展示

## 教程

## 中英日对照

![](https://mir.yuelili.com/user/AE/effects/AE-Effects-Utility-Color_Profile_Converter.png)![](https://mir.yuelili.com/user/AE/effects/AE-Effects-Utility-Color_Profile_Converter_cn.png)

## 参数详解

### 感性

尝试保留颜色之间的视觉关系，以使人眼看起来感觉很自然，尽管颜色值本身可能有改变。此意图适合包含大量超出色域的颜色的图像。

### 饱和度

尝试在降低颜色准确度的情况下生成逼真的颜色。此渲染意图适合其中明亮的饱和颜色比颜色之间的精确关系更加重要的图像，例如图形徽标。

### 相对色度

将源颜色空间的最亮部分与目标颜色空间的最亮部分进行比较并相应地转换所有颜色。超出色域的颜色会转换为目标颜色空间内可重现的最相似的颜色。与“感性”相比，此渲染意图可保留图像中更多的原始颜色。默认情况下，整个
After Effects 中均使用此渲染意图。

### 绝对色度

不改变位于目标色域内的颜色。超出色域的颜色将被剪切掉。不针对目标白场调整颜色。此意图旨在保持颜色准确度而不保留颜色之间的关系。

使用“场景参考配置文件补偿”控件可确定“颜色配置文件转换器”的每个实例是否会补偿场景引用的配置文件：

### 开

补偿场景引用的配置文件。

### 关

不补偿场景引用的配置文件。

### 使用项目设置

使用项目的“补偿场景引用的配置文件”选项指示的设置。

有关场景引用的配置文件的说明，请参阅系统灰度系数、设备灰度系数以及场景与观看环境之间的差异。

**注意**

如果您打开的 After Effects 7 项目使用“颜色配置文件转换器”效果中的 DPX Scene 和 DPX Theater 颜色配置文件，则
After Effects CS5 不会将这些配置文件自动更新为新的等效配置文件（Kodak 5218/7218 Printing Density 和
Kodak 2383 Theater Preview）。相反，这些配置文件将列为“嵌入”。您可以通过在 After Effects CS5
中手动分配新的配置文件来转换您的项目。但是，如果在 After Effects 7
中将相同的配置文件分配给素材或者在“校样颜色”中选择了相同的配置文件，则这些配置文件会自动更新为 After Effects CS5
中的新配置文件。（“校样颜色”已由“输出模拟”取代。）

## 案例
