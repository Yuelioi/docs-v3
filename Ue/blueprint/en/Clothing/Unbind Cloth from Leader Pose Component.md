---
display_name: Unbind Cloth from Leader Pose Component
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Clothing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Clothing)

If this component has a valid LeaderPoseComponent and has previously had its cloth bound to the
MCP, this function will unbind the cloth and resume simulation.

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Restore Simulation Space | if true and the leader pose cloth was originally simulating in world space, we will restore this setting. This will cause the leader component to reset which may be undesirable. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
