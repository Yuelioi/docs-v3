---
display_name: Add Actor World Rotation
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Adds a delta to the rotation of this actor in world space.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| rotator | Delta Rotation | The change in rotation. |
| boolean | Sweep | Whether to sweep to the target rotation (not currently supported for rotation). |
| boolean | Teleport | Whether we teleport the physics state (if physics collision is enabled for this object). If true, physics velocity for this object is unchanged (so ragdoll parts are not affected by change in location). If false, physics velocity is updated based on the change in position (affecting ragdoll parts). If CCD is on and not teleporting, this will affect objects along the entire swept volume. Note that when teleporting, any child/attached components will be teleported too, maintaining their current offset even if they are being simulated. Setting the rotation without teleporting will not update the rotation of simulated child/attached components. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Sweep Hit Result | The hit result from the move if swept. |
