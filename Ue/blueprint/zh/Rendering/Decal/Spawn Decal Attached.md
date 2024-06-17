---
title: Spawn Decal Attached
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Decal](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Decal)

Spawns a decal attached to and following the specified component. Does not replicate.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Decal Material | decal's material |
| vector | Decal Size | size of decal |
| object | Attach to Component |  |
| name | Attach Point Name | Optional named point within the AttachComponent to spawn the emitter at |
| vector | Location | Depending on the value of Location Type this is either a relative offset from the attach component/point or an absolute world position that will be translated to a relative offset |
| rotator | Rotation | Depending on the value of LocationType this is either a relative offset from the attach component/point or an absolute world rotation that will be translated to a realative offset |
| enum | Location Type | Specifies whether Location is a relative offset or an absolute world position |
| real | Life Span | destroy decal component after time runs out (0 = infinite) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
