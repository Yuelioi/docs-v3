---
title: Export to GLTF
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Miscellaneous](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Miscellaneous)

Export the specified object to a glTF file (.gltf or .glb)

Target is GLTFExporter

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The object to export (supported types are UMaterialInterface, UStaticMesh, USkeletalMesh, UWorld, UAnimSequence, ULevelSequence, ULevelVariantSets). Will default to the currently active world if null. |
| string | File Path | The filename on disk to save as. Associated textures and binary files will be saved in the same folder, unless file extension is .glb - which results in a self-contained binary file. |
| object | Options | The various options to use during export. Will default to the project's user-specific editor settings if null. |
| object | Selected Actors | The set of actors to export, only applicable if the object to export is a UWorld. An empty set results in the export of all actors. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Messages | The resulting log messages from the export. |
| boolean | Return Value | true if the object was successfully exported |
