---
title: Schedule Local Notification at Time
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Platform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Platform) > [Local Notification](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Platform/LocalNotification)

Schedule a local notification at a specific time, inLocalTime specifies the current local time or if UTC time should be used

Target is Blueprint Platform Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Fire Date Time | The time at which to fire the local notification |
| boolean | Local Time | If true the provided time is in the local timezone, if false it is in UTC |
| text | Title | The title of the notification |
| text | Body | The more detailed description of the notification |
| text | Action | The text to be displayed on the slider controller |
| string | Activation Event | A string that is passed in the delegate callback when the app is brought into the foreground from the user activating the notification |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value |  |
