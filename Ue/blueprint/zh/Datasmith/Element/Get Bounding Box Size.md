---
display_name: Get Bounding Box Size
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith) > [Element](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith/Element)

Get the Bounding Box of the Actor as a Vector. X is Width, Y is Height, Z is Depth.
The value will are taken from the MeshElement and are factored by the Actor Scale.
Bounding Box size can only be calculated if the Mesh can be found.

Target is Datasmith Mesh Actor Element

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Get the Bounding Box of the Actor as a Vector. X is Width, Y is Height, Z is Depth.The value will are taken from the MeshElement and are factored by the Actor Scale.Bounding Box size can only be calculated if the Mesh can be found. |
