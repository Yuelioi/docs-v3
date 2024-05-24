---
display_name: Set Metadata Field
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Metadata Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/MetadataUtils)

- Utilities that make it easier to get/set metadata fields without having to manipulate the nested struct instances directly.
- It will create the struct entries automatically if needed, and overwrite existing entries with the same key if needed.
  \*
- If the AssetUserData contains exactly one entry for StageIdentifier and one entry for PrimPath, you can omit those arguments
- and that single entry will be used. If there are more or less than exactly one entry for StageIdentifier or for PrimPath however,
- you must specify which one to use, and failing to do so will cause the functions to return false and emit a warning.
  \*
- It is possible to get these functions to automatically trigger pre/post property changed events by providing "true" for
- bTriggerPropertyChangeEvents, which is useful as it is not trivial to trigger those from Python/Blueprint given how the
- metadata is stored inside nested structs and maps. If these AssetUserData belong to generated transient assets when opening
- stages, emitting property change events causes those edits to be immediately written out to the opened USD Stage.
  \*
- Returns true if it managed to set the new key-value pair.

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Asset User Data |  |
| string | Key |  |
| string | Value |  |
| string | Value Type Name |  |
| string | Stage Identifier |  |
| string | Prim Path |  |
| boolean | Trigger Property Change Events |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | *Utilities that make it easier to get/set metadata fields without having to manipulate the nested struct instances directly.* It will create the struct entries automatically if needed, and overwrite existing entries with the same key if needed. **If the AssetUserData contains exactly one entry for StageIdentifier and one entry for PrimPath, you can omit those arguments *and that single entry will be used. If there are more or less than exactly one entry for StageIdentifier or for PrimPath however,* you must specify which one to use, and failing to do so will cause the functions to return false and emit a warning.** It is possible to get these functions to automatically trigger pre/post property changed events by providing "true" for *bTriggerPropertyChangeEvents, which is useful as it is not trivial to trigger those from Python/Blueprint given how the* metadata is stored inside nested structs and maps. If these AssetUserData belong to generated transient assets when opening\* stages, emitting property change events causes those edits to be immediately written out to the opened USD Stage.\*\* Returns true if it managed to set the new key-value pair. |
