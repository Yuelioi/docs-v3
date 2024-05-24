---
display_name: Extract Event Data
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi-user](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_user)

Extract event message data. Given a MultiUserBlueprintEventData extract the message contents and put it into the desired
struct. The struct must match the target type.

Target is MultiUserSubsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Event Data |  |
| wildcard | Struct Out | The a reference to the structure that will receive the data. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
