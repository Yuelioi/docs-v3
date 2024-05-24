---
display_name: Set AR Alignment Transform
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Alignment](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/Alignment)

Set a transform that will be applied to the tracking space. This effectively moves any camera
possessed by the Augmented Reality system such that it is pointing at a different spot
in Unreal's World Space. This is often done to support AR scenarios that rely on static
geometry and/or lighting.

Note: any movable components that are pinned will appear to stay in place, while anything
not pinned or is not movable (static or stationary) will appear to move.

\\see PinComponent
\\see PinComponentToTraceResult

Target is ARBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| transform | In Alignment Transform |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
