---
title: Play Animation with Finished event
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Animation)

Play Animation on widget and trigger Finish event when the animation is done.

Target is Widget Animation Play Callback Proxy

Latent. This node will complete at a later time. Latent nodes can only be placed in event graphs.

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Widget |  |
| object | In Animation |  |
| real | Start at Time |  |
| integer | Num Loops to Play |  |
| enum | Play Mode |  |
| real | Playback Speed |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Result |  |
| exec | Finished | Called when animation has been completed |
