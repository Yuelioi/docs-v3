---
display_name: Load Selected Objects if Needed
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Tool Menus](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ToolMenus)

Loads the selected assets (if needed) which is based on AssetViewUtils::LoadAssetsIfNeeded, this exists primarily
for backwards compatability. Reliance on a black box to determine 'neededness' is not recommended, this function
will likely be deprecated a few versions after GetSelectedObjects.

Target is Content Browser Asset Context Menu Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Loads the selected assets (if needed) which is based on AssetViewUtils::LoadAssetsIfNeeded, this exists primarilyfor backwards compatability. Reliance on a black box to determine 'neededness' is not recommended, this functionwill likely be deprecated a few versions after GetSelectedObjects. |
