---
display_name: Expand By (Box)
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Box](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Box)

Returns a box of increased size.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Box |  |
| vector | Negative | The size to increase the volume by in the negative direction (positive values move the bounds outwards) |
| vector | Positive | The size to increase the volume by in the positive direction (positive values move the bounds outwards) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | A new bounding box. |
