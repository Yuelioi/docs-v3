---
display_name: Get Gameplay Effect Count if Loaded
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Effects](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayEffects)

Get the count of the specified source effect on the ability system component. For non-stacking effects, this is the sum of all active instances.
For stacking effects, this is the sum of all valid stack counts. If an instigator is specified, only effects from that instigator are counted.

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| softclass | Soft Source Gameplay Effect | Effect to get the count of. If this is not currently loaded, the count is 0 |
| object | Optional Instigator Filter Component | If specified, only count effects applied by this ability system component |
| boolean | Enforce on Going Check |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Count of the specified source effect |
