---
display_name: Play Montage
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Montage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Montage)

Plays a Montage on a SkeletalMeshComponent

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Skeletal Mesh Component |  |
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
