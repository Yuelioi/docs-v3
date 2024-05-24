---
display_name: Has Assets
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Does the given path contain assets, optionally also testing sub-paths?

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| name | Package Path | the path to query asset data in (eg, /Game/MyFolder) |
| boolean | Recursive | if true, the supplied path will be tested recursively |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
