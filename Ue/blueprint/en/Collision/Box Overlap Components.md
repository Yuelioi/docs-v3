---
display_name: Box Overlap Components
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Returns an array of components that overlap the given axis-aligned box.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Box Pos | Center of box. |
| vector | Extent |  |
| enum | Object Types |  |
| class | Component Class Filter |  |
| object | Actors to Ignore | Ignore these actors in the list |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Components |  |
| boolean | Return Value | true if there was an overlap that passed the filters, false otherwise. |
