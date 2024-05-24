---
display_name: MoveUpdatedComponent
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Movement](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Movement)

Moves our UpdatedComponent by the given Delta, and sets rotation to NewRotation.
Respects the plane constraint, if enabled.

Target is Movement Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Delta |  |
| rotator | New Rotation |  |
| boolean | Sweep |  |
| boolean | Teleport |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Hit |  |
| boolean | Return Value | True if some movement occurred, false if no movement occurred. Result of any impact will be stored in OutHit. |
