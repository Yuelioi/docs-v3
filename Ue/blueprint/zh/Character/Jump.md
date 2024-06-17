---
title: Jump
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Character](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Character)

Make the character jump on the next update.
If you want your character to jump according to the time that the jump key is held,
then you can set JumpMaxHoldTime to some non-zero value. Make sure in this case to
call StopJumping() when you want the jump's z-velocity to stop being applied (such
as on a button up event), otherwise the character will carry on receiving the
velocity until JumpKeyHoldTime reaches JumpMaxHoldTime.

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
