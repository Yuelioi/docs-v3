---
display_name: Bind Cloth to Leader Pose Component
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Clothing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Clothing)

If this component has a valid LeaderPoseComponent then this function makes cloth items on the follower component
take the transforms of the cloth items on the leader component instead of simulating separately.
Note: This will FORCE any cloth actor on the leader component to simulate in local space. Also
The meshes used in the components must be identical for the cloth to bind correctly

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
