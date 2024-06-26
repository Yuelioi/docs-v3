---
title: Async Save Settings
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Enhanced Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EnhancedInput) > [User Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EnhancedInput/UserSettings)

Asynchronously save the settings to a hardcoded save game slot. This will work for simple games,
but if you need to integrate it into an advanced save system you should Serialize this object out with the rest of your save data.

OnAsyncSaveComplete will be called upon save completion.

Target is Enhanced Input User Settings (Experimental)

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
