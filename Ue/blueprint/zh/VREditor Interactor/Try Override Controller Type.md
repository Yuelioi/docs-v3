---
title: Try Override Controller Type
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [VREditor Interactor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VREditorInteractor)

Temporary set what controller type this is for asymmetric control schemes.
You can't override the controller type when there's already an override.
Remove the temporary controller type with EControllerType::Unknown

Target is VREditor Interactor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | In Controller Type |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the controller type was changed |
