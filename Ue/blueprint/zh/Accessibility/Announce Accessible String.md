---
display_name: Announce Accessible String
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Accessibility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Accessibility)

If accessibility is enabled, have the platform announce a string to the player.
These announcements can be interrupted by system accessibiliity announcements or other accessibility announcement requests.
This should be used judiciously as flooding a player with announcements can be overrwhelming and confusing.
Try to make announcements concise and clear.
NOTE: Currently only supported on Win10, Mac, iOS

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Announcement String |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
