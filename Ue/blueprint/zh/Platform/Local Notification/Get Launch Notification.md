---
display_name: Get Launch Notification
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Platform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Platform) > [Local Notification](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Platform/LocalNotification)

Get the local notification that was used to launch the app

Target is Blueprint Platform Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Notification Launched App | Return true if a notification was used to launch the app |
| string | Activation Event | Returns the name of the ActivationEvent if a notification was used to launch the app |
| integer | Fire Date | Returns the time the notification was activated |
