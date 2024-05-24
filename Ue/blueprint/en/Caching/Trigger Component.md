---
display_name: Trigger Component
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Caching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Caching)

Triggers a component to play or record.
If the cache manager has an observed component entry for InComponent and it is a triggered entry
this will begin the playback or record for that component, otherwise no action is taken.

Target is Chaos Cache Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Component | Component to trigger |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
