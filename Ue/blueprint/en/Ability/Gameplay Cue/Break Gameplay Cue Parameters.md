---
display_name: Break Gameplay Cue Parameters
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Gameplay Cue](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/GameplayCue)

Native break, to avoid having to deal with quantized vector types

Target is Ability System Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Parameters |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Normalized Magnitude |  |
| real | Raw Magnitude |  |
| struct | Effect Context |  |
| struct | Matched Tag Name |  |
| struct | Original Tag |  |
| struct | Aggregated Source Tags |  |
| struct | Aggregated Target Tags |  |
| vector | Location |  |
| vector | Normal |  |
| object | Instigator |  |
| object | Effect Causer |  |
| object | Source Object |  |
| object | Physical Material |  |
| integer | Gameplay Effect Level |  |
| integer | Ability Level |  |
| object | Target Attach Component |  |
| boolean | Replicate Location when Using Minimal Rep Proxy |  |
