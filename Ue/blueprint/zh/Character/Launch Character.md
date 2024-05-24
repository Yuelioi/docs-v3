---
display_name: Launch Character
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Character](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Character)

Set a pending launch velocity on the Character. This velocity will be processed on the next CharacterMovementComponent tick,
and will set it to the "falling" state. Triggers the OnLaunched event.

Target is Character

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Launch Velocity | is the velocity to impart to the Character |
| boolean | XYOverride | if true replace the XY part of the Character's velocity instead of adding to it. |
| boolean | ZOverride | if true replace the Z component of the Character's velocity instead of adding to it. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
