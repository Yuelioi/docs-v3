---
title: Generate Scene View Extension Is Active Functor for Viewport Type
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Production](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualProduction) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualProduction/Rendering)

Returns a functor to activate a scene view extension when the FViewport in the SceneViewExtensionContext is selectively:

- PIE
- SIE
- Editor's active
- Game's primary
  If it is none of the above, it emits no opinion about activating the Scene View Extension.

Target is VPRendering Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | PIE |  |
| boolean | SIE |  |
| boolean | Editor Active |  |
| boolean | Game Primary |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Is Active Function |  |
