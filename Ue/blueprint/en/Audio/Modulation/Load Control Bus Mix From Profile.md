---
title: Load Control Bus Mix From Profile
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Loads control bus mix from a profile into UObject mix definition, deserialized from an ini file.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Mix |  |
| boolean | Activate | If true, activate mix upon loading from profile. |
| integer | Profile Index | Index of profile, allowing multiple profiles to be loaded to single mix object. If \<= 0, loads from default profile (no suffix). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Stages | Stages - Stage values loaded from profile (empty if profile did not exist or had no values serialized). |
