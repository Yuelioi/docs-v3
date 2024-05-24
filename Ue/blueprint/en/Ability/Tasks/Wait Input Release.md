---
display_name: Wait Input Release
order: 38
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the user releases the input button for this ability's activation. Returns time from hitting this node, till release. Will return 0 if input was already released.

Target is Ability Task Wait Input Release

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| boolean | Test Already Released |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Release |  |
| real | Time Held |  |
