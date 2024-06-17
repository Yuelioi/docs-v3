---
title: Register and Call for Actor Init State
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Init State](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/InitState)

Registers blueprint delegate for feature state change notifications on a specific actor and may call it immediately

Target is Game Framework Component Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor | The actor to listen for state changes to, if you don't have a specific actor call the Class version instead |
| name | Feature Name | If not empty, only listen to state changes for the specified feature |
| struct | Required State | If specified, only activate if the init state of the feature is equal to or later than this |
| delegate | Delegate | Native delegate to call |
| boolean | Call Immediately | If true and the actor feature is already in the specified state, call delegate immediately after registering |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if delegate was registered |
