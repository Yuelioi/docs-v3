---
display_name: Set Bone Track Keys (Message)
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationData)

Removes an existing bone animation track with the provided name. Broadcasts a EAnimDataModelNotifyType::TrackChanged notify if successful.
The provided number of keys provided is expected to match for each component, and be non-zero.

Target is Animation Data Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Bone Name | Bone name of the track for which the keys should be set |
| vector | Positional Keys | Array of keys for the translation component |
| struct | Rotational Keys | Array of keys for the rotation component |
| vector | Scaling Keys | Array of keys for the scale component |
| boolean | Should Transact | Whether or not any undo-redo changes should be generated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether or not the keys were successfully set |
