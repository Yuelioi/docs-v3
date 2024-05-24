---
display_name: Play Montage (Mover Actor)
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Montage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Montage)

Plays a Montage on an actor with Mover and SkeletalMesh components. Used for networked animation root motion.

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Mover Component |  |
| object | Montage to Play |  |
| real | Play Rate |  |
| real | Starting Position |  |
| name | Starting Section |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Completed | Called when Montage finished playing and wasn't interrupted |
| exec | On Blend Out | Called when Montage starts blending out and is not interrupted |
| exec | On Interrupted | Called when Montage has been interrupted (or failed to play) |
| exec | On Notify Begin |  |
| exec | On Notify End |  |
| name | Notify Name |  |
