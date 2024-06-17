---
title: Reset All Player Keys in Row
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Enhanced Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EnhancedInput) > [User Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EnhancedInput/UserSettings)

Resets each player mapped key to it's default value from the Input Mapping Context that it was registered from.
If a key did not come from an IMC (i.e. it was added additionally by the player) then it will be reset to EKeys::Invalid.

Target is Enhanced Input User Settings (Experimental)

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Args | Arguments that contain the mapping name and profile ID to find the mapping to reset. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Failure Reason | Populated with failure reasons if the operation fails. |
