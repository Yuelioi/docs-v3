---
display_name: Resolve Buffer
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Capture](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Capture)

- Resolve the specified buffer and pass it directly to the specified handler when done (does not pass to any bound streams)

Target is Capture Protocol

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Buffer | The desired buffer to save * |
| struct | Buffer ID | The ID of this buffer that is passed to the pixel handler (e.g. a composition pass name). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
