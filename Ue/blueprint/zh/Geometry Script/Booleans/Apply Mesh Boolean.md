---
display_name: Apply Mesh Boolean
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Booleans](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Booleans)

Applies a Boolean operation (such as, Union, Intersect, and Subtract) to the Target Dynamic Mesh based on a Tool Dynamic Mesh.

Target is Geometry Script Library Mesh Boolean Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | Dynamic Mesh to be acted upon |
| transform | Target Transform | used to position the TargetMesh |
| object | Tool Mesh | Dynamic Mesh that acts as the cutting tool |
| transform | Tool Transform | used to position the ToolMesh |
| enum | Operation | selects the specific boolean operation |
| struct | Options | selects additional options that are applied to the result |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
