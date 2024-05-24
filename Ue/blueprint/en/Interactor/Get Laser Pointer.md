---
display_name: Get Laser Pointer
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interactor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interactor)

Gets the start and end point of the laser pointer for the specified hand

Target is Viewport Interactor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Even if Blocked | If true, returns a laser pointer even if the hand has UI in front of it (defaults to false) |
| real | Laser Length Override | If zero the default laser length (VREdMode::GetLaserLength) is used |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Laser Pointer Start |  |
| vector | Laser Pointer End |  |
| boolean | Return Value | True if we have motion controller data for this hand and could return a valid result |
