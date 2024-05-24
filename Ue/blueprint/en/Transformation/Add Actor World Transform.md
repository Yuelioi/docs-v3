---
display_name: Add Actor World Transform
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Adds a delta to the transform of this actor in world space. Ignores scale and sets it to (1,1,1).

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| transform | Delta Transform |  |
| boolean | Sweep |  |
| boolean | Teleport |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Sweep Hit Result |  |
