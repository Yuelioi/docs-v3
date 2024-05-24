---
display_name: Box Overlap Actors
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Returns an array of actors that overlap the given axis-aligned box.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Box Pos | Center of box. |
| vector | Box Extent | Extents of box. |
| enum | Object Types |  |
| class | Actor Class Filter |  |
| object | Actors to Ignore | Ignore these actors in the list |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Actors | Returned array of actors. Unsorted. |
| boolean | Return Value | true if there was an overlap that passed the filters, false otherwise. |
