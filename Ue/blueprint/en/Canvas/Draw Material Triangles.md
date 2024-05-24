---
display_name: Draw Material Triangles
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Canvas)

Draws a set of triangles on the Canvas.

Target is Canvas

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Render Material | Material to use when rendering. Remember that only the emissive channel is able to be rendered as no lighting is performed when rendering to the Canvas. |
| struct | Triangles | Triangles to render. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
