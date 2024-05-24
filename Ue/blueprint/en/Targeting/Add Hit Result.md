---
display_name: Add Hit Result
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Targeting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Targeting)

Adds a HitResult to the Targeting Results for a given TargetingRequestHandle.
Returns False when the Actor that was hit was already in the list

Target is Simple Targeting Selection Task

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Targeting Handle |  |
| struct | Hit Result |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Adds a HitResult to the Targeting Results for a given TargetingRequestHandle.Returns False when the Actor that was hit was already in the list |
