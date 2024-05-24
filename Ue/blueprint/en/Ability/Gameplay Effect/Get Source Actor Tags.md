---
display_name: Get Source Actor Tags
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Gameplay Effect](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/GameplayEffect)

Returns the source actor tags from a Gameplay Effect Spec

Target is Gameplay Mod Magnitude Calculation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Effect Spec | The Gameplay Effect Spec to get the info from |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Gameplay Tag Container with the copied tags. The container will be empty if no captured source tags exist. |
