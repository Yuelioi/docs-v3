---
title: Import Scene
order: 44
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith) > [Scene](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith/Scene)

Import a Datasmith Scene created with ConstructDatasmithSceneFromFile.

Target is Datasmith Scene Element

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Destination Folder | Destination of where you want the asset to be imported. ie: /Game/MyFolder1 |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | A structure that contains the created actor or the blueprint actor depending of the options specified at the import. |
