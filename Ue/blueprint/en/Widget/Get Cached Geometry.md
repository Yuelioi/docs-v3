---
display_name: Get Cached Geometry
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget)

Gets the last geometry used to Tick the widget. This data may not exist yet if this call happens prior to
the widget having been ticked/painted, or it may be out of date, or a frame behind.

We recommend not to use this data unless there's no other way to solve your problem. Normally in Slate we
try and handle these issues by making a dependent widget part of the hierarchy, as to avoid frame behind
or what are referred to as hysteresis problems, both caused by depending on geometry from the previous frame
being used to advise how to layout a dependent object the current frame.

Target is Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Gets the last geometry used to Tick the widget. This data may not exist yet if this call happens prior tothe widget having been ticked/painted, or it may be out of date, or a frame behind.We recommend not to use this data unless there's no other way to solve your problem. Normally in Slate wetry and handle these issues by making a dependent widget part of the hierarchy, as to avoid frame behindor what are referred to as hysteresis problems, both caused by depending on geometry from the previous framebeing used to advise how to layout a dependent object the current frame. |
