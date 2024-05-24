---
display_name: Set Stage Root Layer
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Export Context](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ExportContext)

Opens or creates a USD stage using `StageRootLayerPath` as root layer, creating the root layer if needed.
All future conversions will fetch prims and get/set USD data to/from this stage.
Note: You must remember to call Cleanup() when done, or else this object will permanently hold a reference to the opened stage!

Target is Usd Conversion Blueprint Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Stage Root Layer Path |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
