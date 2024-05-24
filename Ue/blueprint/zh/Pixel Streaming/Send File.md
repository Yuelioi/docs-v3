---
display_name: Send File
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pixel Streaming](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PixelStreaming)

Send a specified file over the WebRTC peer connection data channel. The extension and mime type are used for file reconstruction on the front end

Target is Pixel Streaming Blueprints

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Filepath | The path to the file that will be sent |
| string | Mime Type | The mime type of the file. Used for file reconstruction on the front end |
| string | File Extension | The file extension. Used for file reconstruction on the front end |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
