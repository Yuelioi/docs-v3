---
display_name: Send File as Byte Array
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pixel Streaming](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PixelStreaming)

Send a specified byte array over the WebRTC peer connection data channel. The extension and mime type are used for file reconstruction on the front end

Target is Pixel Streaming Blueprints

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| byte | Byte Array | The raw data that will be sent over the data channel |
| string | Mime Type | The mime type of the file. Used for reconstruction on the front end |
| string | File Extension | The file extension. Used for file reconstruction on the front end |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
