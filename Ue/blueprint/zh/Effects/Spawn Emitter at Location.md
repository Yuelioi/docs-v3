---
display_name: Spawn Emitter at Location
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Effects](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Effects)

Plays the specified effect at the given location and rotation, fire and forget. The system will go away when the effect is complete. Does not replicate.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Emitter Template | particle system to create |
| vector | Location | location to place the effect in world space |
| rotator | Rotation | rotation to place the effect in world space |
| vector | Scale | scale to create the effect at |
| boolean | Auto Destroy | Whether the component will automatically be destroyed when the particle system completes playing or whether it can be reactivated |
| enum | Pooling Method | Method used for pooling this component. Defaults to none. |
| boolean | Auto Activate System |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
