---
display_name: Register and Call for Class Init State
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Init State](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/InitState)

Registers blueprint delegate for feature state change notifications on a class of actors and may call it immediately

Target is Game Framework Component Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| softclass | Actor Class | Name of an actor class to listen for changes to |
| name | Feature Name | If not empty, only listen to state changes for the specified feature |
| struct | Required State | If specified, only activate if the init state of the feature is equal to or later than this |
| delegate | Delegate | Native delegate to call |
| boolean | Call Immediately | If true and the actor feature is already in the specified state, call delegate immediately after registering |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if delegate was registered |
