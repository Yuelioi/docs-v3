---
display_name: Send Socket Message
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Sends a socket message if the socket is currently connected. Messages back will happen in the OnSocketMessageRecieved event.

Target is Movie Pipeline Executor Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Message | The message to send. This will be sent over the socket (if connected) with a 4 byte (int32) size prefix on the message so the recieving end knows how much data to recieve before considering it done. This prevents accidentally chopping json strings in half. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the message was sent succesfully. |
