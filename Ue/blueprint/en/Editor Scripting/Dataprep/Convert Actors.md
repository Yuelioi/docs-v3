---
display_name: Convert Actors
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Dataprep)

Replace in the level all Actors provided with a new actor of type ActorClass. Destroy all Actors provided.

Target is Editor Actor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actors | List of Actors to replace. |
| class | Actor Class | Class/Blueprint of the new actor that will be spawn. |
| string | Static Mesh Package Path | If the list contains Brushes and it is requested to change them to StaticMesh, StaticMeshPackagePath is the package path to where the StaticMesh will be created. ie. /Game/MyFolder/ |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
