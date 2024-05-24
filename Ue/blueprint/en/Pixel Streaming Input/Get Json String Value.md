---
display_name: Get Json String Value
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pixel Streaming Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PixelStreamingInput)

Helper function to extract a string field from a JSON descriptor of a
UI interaction given its field name.
The field name may be hierarchical, delimited by a period. For example,
to access the Width value of a Resolution command above you should use
"Resolution.Width" to get the width value.

Target is Pixel Streaming Input

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| string | Descriptor | The UI interaction JSON descriptor. |
| string | Field Name | The name of the field to look for in the JSON. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | String Value | The string value associated with the field name. |
| boolean | Success | True if the field exists in the JSON data. |
