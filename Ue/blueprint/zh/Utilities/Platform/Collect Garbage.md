---
display_name: Collect Garbage
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Platform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Platform)

Deletes all unreferenced objects, keeping only referenced objects (this command will be queued and happen at the end of the frame)
Note: This can be a slow operation, and should only be performed where a hitch would be acceptable

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |