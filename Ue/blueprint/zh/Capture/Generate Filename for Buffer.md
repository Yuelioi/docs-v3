---
display_name: Generate Filename for Buffer
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Capture](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Capture)

- Generate a filename for the specified buffer using this protocol's file name formatter

Target is Capture Protocol

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Buffer | The desired buffer to generate a filename for * |
| struct | Stream ID | The ID of the stream for this buffer (e.g. a composition pass name) * |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | A fully qualified file name |
