---
display_name: Touch or Precache MetaSound
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Meta Sound](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MetaSound)

same as PrecacheMetaSound except cached operator that already exists in the cache will be moved to the top instead of building,
any operators that we couldn't move to the top, will be built.
(i.e. if 2 operators are already cached and Num Instances is 4, it will construct 2 and move the existing 2 to the top of the cache)

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
