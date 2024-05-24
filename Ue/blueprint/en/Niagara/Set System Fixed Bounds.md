---
display_name: Set System Fixed Bounds
order: 67
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Niagara)

Sets the fixed bounds for the system instance, this overrides all other bounds.
The box is expected to be in local space not world space.
A default uninitialized box will clear the fixed bounds and revert back to system fixed / dynamic bounds.

Target is Niagara Particle System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Local Bounds |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
