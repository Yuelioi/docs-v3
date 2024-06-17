---
title: Try Walk to Slide Along Surface
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover)

Attempts to move a component along a surface in the walking mode. Returns the percent of time applied, with 0.0 meaning no movement occurred.
Note: This modifies the normal and calls UMovementUtils::TryMoveToSlideAlongSurface

Target is Ground Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Updated Component |  |
| object | Updated Primitive |  |
| object | Mover Component |  |
| vector | Delta |  |
| real | Pct Of Delta to Move |  |
| struct | Rotation |  |
| vector | Normal |  |
| boolean | Handle Impact |  |
| real | Max Walk Slope Cosine |  |
| real | Max Step Height |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Hit |  |
| struct | Move Record |  |
| real | Return Value | Attempts to move a component along a surface in the walking mode. Returns the percent of time applied, with 0.0 meaning no movement occurred.Note: This modifies the normal and calls UMovementUtils::TryMoveToSlideAlongSurface |
