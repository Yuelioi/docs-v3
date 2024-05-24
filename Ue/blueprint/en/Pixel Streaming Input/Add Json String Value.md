---
display_name: Add Json String Value
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pixel Streaming Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PixelStreamingInput)

Helper function to add a string field to a JSON descriptor. This produces
a new descriptor which may then be chained to add further string fields.

Target is Pixel Streaming Input

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| string | Descriptor | The initial JSON descriptor which may be blank initially. |
| string | Field Name | The name of the field to add to the JSON. |
| string | String Value | The string value associated with the field name. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | New Descriptor | The JSON descriptor with the string field added. |
| boolean | Success | True if the string field could be added successfully. |
