---
display_name: Get Socket Transform
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Get world-space socket transform.

Target is Scene Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | In Socket Name | Name of the socket or the bone to get the transform |
| enum | Transform Space |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | Socket transform in world space if socket if found. Otherwise it will return component's transform in world space. |
