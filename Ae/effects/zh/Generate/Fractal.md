---
title: 分形
order: 17
---

# Fractal - 分形

## 简述

分形效果可渲染曼德布罗特或朱莉娅集合，从而创建多彩的纹理。在首次应用此效果时，您看到的图片是曼德布罗特集合的经典样本；此集合是使用黑色着色的区域。此集合外部的所有像素根据接近此集合的程度进行着色。

此效果适用于 8-bpc 和 16-bpc 颜色。

## 效果展示

有用么这个效果。。。感觉预览图都贼丑，不放了。

## 教程

## 中英日对照

![](https://mir.yuelili.com/user/AE/effects/AE-Effects-Generate-Fractal.png)![](https://mir.yuelili.com/user/AE/effects/AE-Effects-Generate-Fractal_cn.png)

## 参数详解

设置选项

指定使用的集合。“曼德布罗特”是典型的曼德布罗特集合。“曼德布罗特反向”是以数学方式反转的曼德布罗特集合。“朱莉娅”始终根据曼德布罗特集合的中心点改变，并且可产生所有可能的朱莉娅集合的集合。“朱莉娅反向”是朱莉娅集合的反向。要查看朱莉娅集合，可能要将放大率设置为负值，因为这些集合常常用于填充普通边界外部的复平面。除了在朱莉娅中心点改变时“曼德布罗特在朱莉娅上”会改变以外，“曼德布罗特在朱莉娅上”与“曼德布罗特”相同。除了在朱莉娅中心点改变时“曼德布罗特反向在朱莉娅上”会改变以外，“曼德布罗特反向在朱莉娅上”与“曼德布罗特反向”相同。

曼德布罗特、朱莉娅

指定指定集合的设置。“X（真实的）”和“Y（虚构的）”用于指定曼德布罗特或朱莉娅集合图像的中心像素。“放大率”用于指定效果的放大率。“扩展限制”用于在分配黑色之前，指定计算为给定像素寻找颜色的次数。在跟踪某点的路径时，它还可设置选择工具使用的最多线段数。数量越多，渲染时间越长。

颜色

指定效果的颜色：

叠加

显示相对集合的重影版本。例如，在查看朱莉娅集合时，使用此控件可显示曼德布罗特集合的重影版本。在选择“叠加”时，将显示带有黑色投影的白色十字线，以使您可以看到相对集合中心的精确点。此控件很有用，因为朱莉娅集合取决于曼德布罗特集合的中心点。

透明度

指定黑色像素是否透明。如果从“调色板”菜单中选择“纯色”，则此控件可指定集合内外的内容是否透明。

调色板

指定绘制集合时使用的调色板。“亮度渐变”用于创建从黑色延伸到白色，经过“色相”控件指定的色相的渐变效果。然后将同一渐变效果再应用八次，每次都使用色轮上
45°
的色相。“循环步骤”控件用于指定渐变中的颜色数量。“色相轮”用于使用“色相”色轮的所有颜色，以及最高亮度和饱和度。“黑白”用于使用黑白交互带。“纯色”可将除集合内部之外的所有内容变为透明的，集合内部使用“色相”控件指定的颜色。选择“透明”可获得相对的结果。

色相

指定纯色的色相和颜色渐变的起始色相。此控件特别适合创建平滑的颜色变化，或循环使用调色板。“循环步骤”用于指定循环重新开始前显示的不同颜色的色带数。“循环位移”用于指定循环开始的非开头位置。

边缘高光

对色带之间的边缘使用高光。此控件需要低品质模式。如果要使用高品质边缘高光，请改用“查找边缘”效果。

高品质设置

指定效果的过采样设置：

过采样方法

指定对效果过采样所使用的方法：“边缘检测 - 快 -
可能缺失像素”可执行简单的边缘检测，并仅对那些像素过采样。此选项是最快的方法，特别是在有大量纯色（如黑色）的区域中，它产生的结果通常与“强力攻击”难以区分。“强力攻击

- 慢 - 每个像素”可对图像中的每个像素过采样。速度虽慢，但很精确。

过采样因素

指定要执行的过采样的数量。例如，值为 4，则指定对每个像素采样 16 次 (4x4=16)，然后使用平均颜色。值越高，品质输出越好，但渲染时间越长。

### 结合使用分形效果和工具

在“效果控件”面板中选择“分形”效果时，可以按以下方式使用 After Effects 工具。（如果不想激活“分形”工具，则在使用工具之前取消选择此效果。）

- 按住 Alt (Windows) 或 Option (Mac OS) 键时使用选择工具，然后单击。如果此路径直通有界矩形 (-2, -2, 2, 2)，则已达到无限程度；在这样的情况下，起始点颜色基于达到无限程度需要的线段数量。如果此路径在矩形中终止，则使用黑色着色。
- 使用缩放工具在特定点上放大或缩小，或按住 Ctrl 键 (Windows) 或 Command 键 (Mac OS)，在图像中心上单击并按住放大工具，并从中心导航。例如，要放大直线，请停留在中心；要上移，请向上拖动一点，然后快速移回中心。
- 使用抓手工具平移图像。按 Ctrl 键 (Windows) 或 Command 键 (Mac OS)，以平移相对的分形。例如，在查看朱莉娅集合时，按 Ctrl 键 (Windows) 或 Command 键 (Mac OS)，可平移曼德布罗特集合，并查看朱莉娅集合依赖于曼德布罗特集合中心点的程度。
- 使用箭头键将中心点平移 1 个像素。在按箭头键时按 Shift 键，以将此点调整 10 个像素。在按箭头键时按 Ctrl 键 (Windows) 或 Command 键 (Mac OS)，以调整相对集合的中心点。
