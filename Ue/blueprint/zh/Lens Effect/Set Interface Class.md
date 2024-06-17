---
title: Set Interface Class
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lens Effect](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LensEffect)

Set the represented class of the passed in variable. Note: Check the tooltips on the individual pins.
You cannot bypass the validation by connecting a wires to this node!!

Target is Camera Lens Effect Interface Class Support Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Class | MUST implement CameraLensEffectInterface - when connecting variables to the input, take care that the input class does in fact implement the interface. |
| struct | Var | The wrapper (for validation purposes) of the lens effect class. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Valid |  |
| exec | Invalid |  |
