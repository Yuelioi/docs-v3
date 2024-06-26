---
title: Predict World Transform at Time
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Cinematics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Cinematics)

Initiate an asynchronous prediction for the specified component's world transform at a specific time in a sequence
Changes in attachment between the sequence's current time, and the predicted time are not accounted for
Calling this function on a stopped sequence player is undefined.

Target is Movie Scene Async Action Sequence Prediction

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player | An active, currently playing sequence player to use for predicting the transform |
| object | Target Component | The component to predict a world transform for |
| real | Time in Seconds | The time within the sequence to predict the transform at |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An asynchronous prediction object that contains Result and Failure delegates |
