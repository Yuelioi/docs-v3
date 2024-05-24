---
display_name: Client Start Camera Shake
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Feedback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Feedback)

Play Camera Shake

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Shake | Camera shake animation to play |
| real | Scale | Scalar defining how "intense" to play the anim |
| enum | Play Space | Which coordinate system to play the shake in (used for CameraAnims within the shake). |
| rotator | User Play Space Rot | Matrix used when PlaySpace = CAPS_UserDefined |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
