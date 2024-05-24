---
display_name: Create Answer
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pixel Streaming](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PixelStreaming)

Creates an answer to the given offer objet that was provided.

Target is PixelStreaming Peer Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Offer | The offer SDP string to create an answer for. Should be obtained from the signalling server On Offer event. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The answer object generated. Send this to the signalling server to complete negotiation. |
