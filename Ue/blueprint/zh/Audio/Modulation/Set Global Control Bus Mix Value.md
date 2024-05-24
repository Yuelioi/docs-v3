---
display_name: Set Global Control Bus Mix Value
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Sets a Global Control Bus Mix with a single stage associated with the provided Bus to the given float value. This call should
be reserved for buses that are to be always active. It is *NOT* recommended for transient buses, as not calling clear can keep
buses active indefinitely.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Bus | Bus associated with mix to update |
| real | Value | Value to set global stage to. |
| real | Fade Time | Fade time to user when interpolating between current value and new value. If negative, falls back to last fade time set on stage. If fade time never set on stage, defaults to 100ms. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
