---
title: Begin XRSession
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [XRTracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/XRTracking)

Begin an XR session with the provided input mapping. This will make the tracking system aware of the actions and bindings that are used for XR motion controllers.
Attaching input configs to the session can only be done once, so this is a helper function to attach the input mapping contexts and start the XR session correctly.

Target is Open XRInput Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Input Mapping Contexts | The set of input mapping contexts used for XR |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | False if the input mapping contexts can't be attached to the session, true otherwise |
