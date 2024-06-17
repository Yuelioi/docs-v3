---
title: Try Activate Ability
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Abilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Abilities)

Attempts to activate the given ability, will check costs and requirements before doing so.
Returns true if it thinks it activated, but it may return false positives due to failure later in activation.
If bAllowRemoteActivation is true, it will remotely activate local/server abilities, if false it will only try to locally activate the ability

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Ability to Activate |  |
| boolean | Allow Remote Activation |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Attempts to activate the given ability, will check costs and requirements before doing so.Returns true if it thinks it activated, but it may return false positives due to failure later in activation.If bAllowRemoteActivation is true, it will remotely activate local/server abilities, if false it will only try to locally activate the ability |
