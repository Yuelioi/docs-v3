---
display_name: Get Vertex Weights
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Weights](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Weights)

Get all bone weights for a single vertex.

Target is Skin Weight Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Vertex ID | the index of the vertex |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Return Value | a map of Bone Name to weight values for all bones that influence the specified vertex. |
