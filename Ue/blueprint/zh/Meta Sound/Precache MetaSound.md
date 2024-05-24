---
display_name: Precache MetaSound
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Meta Sound](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MetaSound)

Builds the requested number of MetaSound operators (asynchronously) and puts them in the pool for playback.
(If these operators are not yet available when the MetaSound attempts to play, one will be created Independent of this request.)

Target is Meta Sound Cache Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Meta Sound Source |  |
| integer | Num Instances |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
