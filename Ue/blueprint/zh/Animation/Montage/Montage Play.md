---
display_name: Montage Play
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Montage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Montage)

Plays an animation montage. Returns the length of the animation montage in seconds. Returns 0.f if failed to play.

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Montage to Play |  |
| real | In Play Rate |  |
| enum | Return Value Type |  |
| real | In Time to Start Montage At |  |
| boolean | Stop All Montages |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | Plays an animation montage. Returns the length of the animation montage in seconds. Returns 0.f if failed to play. |
