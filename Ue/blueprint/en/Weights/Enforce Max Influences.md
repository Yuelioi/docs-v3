---
display_name: Enforce Max Influences
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Weights](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Weights)

Strips out smallest influences to ensure each vertex does not have weight on more influences than MaxInfluences.
Influences with the smallest weight are culled first.

Target is Skin Weight Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Max Influences | The maximum number of influences to allow for each vertex in the mesh. If -1 is passed, will use the project-wide MaxInfluences amount. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if influences were removed, false otherwise |
