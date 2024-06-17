---
title: Register Input Mapping Context
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Enhanced Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EnhancedInput) > [User Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EnhancedInput/UserSettings)

Registers this mapping context with the user settings. This will iterate all the key mappings
in the context and create an initial Player Mappable Key for every mapping that is marked as mappable.

Target is Enhanced Input User Settings (Experimental)

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | IMC |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Registers this mapping context with the user settings. This will iterate all the key mappingsin the context and create an initial Player Mappable Key for every mapping that is marked as mappable. |
