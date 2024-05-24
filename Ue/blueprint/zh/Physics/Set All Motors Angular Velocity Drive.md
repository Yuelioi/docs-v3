---
display_name: Set All Motors Angular Velocity Drive
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Enable or Disable AngularVelocityDrive. If motor is in SLERP mode it will be turned on if either EnableSwingDrive OR EnableTwistDrive are enabled. In Twist and Swing mode the twist and the swing can be controlled individually.

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Swing Drive |  |
| boolean | Enable Twist Drive |  |
| boolean | Skip Custom Physics Type |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
