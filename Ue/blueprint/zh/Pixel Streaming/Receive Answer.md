---
title: Receive Answer
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pixel Streaming](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PixelStreaming)

Receives an answer from a streamer after we've sent an offer to receive.

Target is PixelStreaming Peer Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Offer | The answer SDP. Should be obtained from the signalling server On Answer event. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
