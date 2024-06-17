---
title: Detach From Component
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Detach this component from whatever it is attached to. Automatically unwelds components that are welded together (see AttachToComponent), though note that some effects of welding may not be undone.

Target is Scene Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | Location Rule | How to handle translations when detaching. |
| enum | Rotation Rule | How to handle rotation when detaching. |
| enum | Scale Rule | How to handle scales when detaching. |
| boolean | Call Modify | If true, call Modify() on the component and the current attach parent component |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
