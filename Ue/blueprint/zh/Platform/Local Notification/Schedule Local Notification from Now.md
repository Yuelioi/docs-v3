---
title: Schedule Local Notification from Now
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Platform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Platform) > [Local Notification](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Platform/LocalNotification)

Schedule a local notification to fire inSecondsFromNow from now

Target is Blueprint Platform Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | In Seconds from Now | The seconds until the notification should fire |
| text | Title | The title of the notification |
| text | Body | The more detailed description of the notification |
| text | Action | The text to be displayed on the slider controller |
| string | Activation Event | A string that is passed in the delegate callback when the app is brought into the foreground from the user activating the notification |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value |  |
