---
display_name: Get Query Results as Actors
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [EQS](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/EQS)

Outputs an array filled with resulting actors. Note that it makes sense only if ItemType is a EnvQueryItemType_ActorBase-derived type. Returns false if there is no valid result.

Target is EQS Query Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Result Actors |  |
| boolean | Return Value | Outputs an array filled with resulting actors. Note that it makes sense only if ItemType is a EnvQueryItemType_ActorBase-derived type. Returns false if there is no valid result. |
