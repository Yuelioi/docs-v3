---
display_name: Find Collision UV
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Try and find the UV for a collision impact. Note this ONLY works if 'Support UV From Hit Results' is enabled in Physics Settings.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Hit |  |
| integer | UVChannel |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | UV |  |
| boolean | Return Value | Try and find the UV for a collision impact. Note this ONLY works if 'Support UV From Hit Results' is enabled in Physics Settings. |
