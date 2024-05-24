---
display_name: Properties
order: 3
---

# 属性

当您向图层添加蒙版、效果、绘画或文本时，After Effects 会将新属性添加到"时间轴"面板中。这些属性太多，无法在此列出，因此请使用关联器了解在表达式中引用它们的语法。

## anchorPoint

说明：锚点值

类型：[2 或 3 维]数组

## position

说明：在世界空间中返回图层的位置值（如果图层没有父级）。如果图层有父级，则会在父图层的坐标系中（在父图层的图层空间中）返回图层的位置值。

类型：[2 或 3 维]数组

## scale

说明：图层的缩放值，表示为百分比。

类型：[2 或 3 维]数组

## rotation

说明：返回图层的旋转值（以度为单位）。对于 3D 图层，还会返回 z 旋转值（以度为单位）。

类型：[2 或 3 维]数组

## opacity

说明：图层的不透明度值，表示为百分比。

类型：数值。

## audioLevels

说明：返回图层的音频级别属性的值（以分贝为单位）。此值是 2D 值；分别表示左音声道和右声道。不是原始音频的分贝，可能会受关键帧影响。

返回类型： [2]数组。

## timeRemap

说明：如果启用时间重映射，则返回时间重映射属性的值。

类型：数值。

## marker

说明：图层的标记

详见 marker 章

示例：

```javascript
thisLayer.marker.key(1).time; //返回本图层第1个标记点的时间值
```

## name

说明：返回图层的名称。

类型：字符串。

示例：

```javascript
thisLayer.name; //"text layer"
```