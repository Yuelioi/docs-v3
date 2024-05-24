---
display_name: Set Actor Transform
order: 66
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Set the Actors transform to the specified one.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| transform | New Transform | The new transform. |
| boolean | Sweep | Whether we sweep to the destination location, triggering overlaps along the way and stopping short of the target if blocked by something. Only the root component is swept and checked for blocking collision, child components move without sweeping. If collision is off, this has no effect. |
| boolean | Teleport | Whether we teleport the physics state (if physics collision is enabled for this object). If true, physics velocity for this object is unchanged (so ragdoll parts are not affected by change in location). If false, physics velocity is updated based on the change in position (affecting ragdoll parts). If CCD is on and not teleporting, this will affect objects along the entire swept volume. Note that when teleporting, any child/attached components will be teleported too, maintaining their current offset even if they are being simulated. Setting the transform without teleporting will not update the transform of simulated child/attached components. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Sweep Hit Result |  |
| boolean | Return Value |  |
