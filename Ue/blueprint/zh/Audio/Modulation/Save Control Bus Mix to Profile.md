---
display_name: Save Control Bus Mix to Profile
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Saves control bus mix to a profile, serialized to an ini file. If mix is loaded, uses current proxy's state.
If not, uses default UObject representation.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Mix |  |
| integer | Profile Index | Index of profile, allowing multiple profiles can be saved for single mix object. If 0, saves to default ini profile (no suffix). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
