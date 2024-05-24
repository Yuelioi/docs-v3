---
display_name: Apply Displace from Texture Map
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Deformations](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Deformations)

Applies a displacement to a Dynamic Mesh based on a Texture2D and a UV Channel.

Target is Geometry Script Library Mesh Deform Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Texture |  |
| struct | Selection | if non-empty, only the vertices identified by the selection will be subject to displacement, otherwise the Options' EmptyBehavior will be followed. |
| struct | Options |  |
| integer | UV Channel |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
