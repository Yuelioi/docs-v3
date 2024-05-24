---
display_name: Try Activate Abilities by Tag
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Abilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Abilities)

Attempts to activate every gameplay ability that matches the given tag and DoesAbilitySatisfyTagRequirements().
Returns true if anything attempts to activate. Can activate more than one ability and the ability may fail later.
If bAllowRemoteActivation is true, it will remotely activate local/server abilities, if false it will only try to locally activate abilities.

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Gameplay Tag Container |  |
| boolean | Allow Remote Activation |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Attempts to activate every gameplay ability that matches the given tag and DoesAbilitySatisfyTagRequirements().Returns true if anything attempts to activate. Can activate more than one ability and the ability may fail later.If bAllowRemoteActivation is true, it will remotely activate local/server abilities, if false it will only try to locally activate abilities. |
