---
display_name: Show External Login UI
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online)

Shows the login UI for the currently active online subsystem, if the subsystem supports a login UI.

Target is Show Login UICallback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Player Controller |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when there is a successful query |
| exec | On Failure | Called when there is an unsuccessful query |
| object | Player Controller |  |
