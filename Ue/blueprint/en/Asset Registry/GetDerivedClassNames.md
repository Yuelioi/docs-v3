---
display_name: GetDerivedClassNames
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Returns the names of all classes derived by the supplied class names, excluding any classes matching the excluded class names. This can be slow if temporary caching mode is not on

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | Class Names |  |
| struct | Excluded Class Names |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Derived Class Names |  |
