---
display_name: Stop Jumping
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Character](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Character)

Stop the character from jumping on the next update.
Call this from an input event (such as a button 'up' event) to cease applying
jump Z-velocity. If this is not called, then jump z-velocity will be applied
until JumpMaxHoldTime is reached.

Target is Character

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
