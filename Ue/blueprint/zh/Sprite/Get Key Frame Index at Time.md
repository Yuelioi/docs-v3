---
display_name: Get Key Frame Index at Time
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sprite](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sprite)

Returns the keyframe index that covers the specified time (in seconds), or INDEX_NONE if none exists.
When bClampToEnds is true, it will choose the first or last keyframe if the time is out of range.

Target is Paper Flipbook

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Time |  |
| boolean | Clamp to Ends |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Returns the keyframe index that covers the specified time (in seconds), or INDEX_NONE if none exists.When bClampToEnds is true, it will choose the first or last keyframe if the time is out of range. |
