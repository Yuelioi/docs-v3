---
display_name: Load Level Instance (by Name)
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Streaming](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelStreaming)

Stream in a level with a specific location and rotation. You can create multiple instances of the same level!

The level to be loaded does not have to be in the persistent map's Levels list, however to ensure that the .umap does get
packaged, please be sure to include the .umap in your Packaging Settings:

Project Settings -> Packaging -> List of Maps to Include in a Packaged Build (you may have to show advanced or type in filter)

Target is Level Streaming Dynamic

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Level Name | Level package name to load, ex: /Game/Maps/MyMapName, specifying short name like MyMapName will force very slow search on disk |
| vector | Location | World space location where the level should be spawned |
| rotator | Rotation | World space rotation for rotating the entire level |
| string | Optional Level Name Override | If set, the loaded level package have this name, which is used by other functions like UnloadStreamLevel. Note this is necessary for server and client networking because the level must have the same name on both. |
| class | Optional Level Streaming Class | If set, the level streaming class will be used instead of ULevelStreamingDynamic |
| boolean | Load as Temp Package | If set, package path is prefixed by /Temp |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Out Success | Whether operation was successful (map was found and added to the sub-levels list) |
| object | Return Value | Streaming level object for a level instance |
