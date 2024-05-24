---
display_name: Capsule Overlap Components
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Returns an array of components that overlap the given capsule.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Capsule Pos | Center of the capsule. |
| real | Radius | Radius of capsule hemispheres and radius of center cylinder portion. |
| real | Half Height | Half-height of the capsule (from center of capsule to tip of hemisphere. |
| enum | Object Types |  |
| class | Component Class Filter |  |
| object | Actors to Ignore | Ignore these actors in the list |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Components |  |
| boolean | Return Value | true if there was an overlap that passed the filters, false otherwise. |
