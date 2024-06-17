---
title: Get Pixel Linear Color
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Shared Image](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SharedImage)

Returns the color value for the given pixel. If the input position is invalid, the format is invalid,
or the reference isn't set, bValid will be false and the function will return FailureColor. The color
is converted using the image's gamma space in to linear space.

Do not use this for full image processing as it will be extremely slow, contact support if you need such
functionality.

Target is Shared Image Const Ref Blueprint Fns

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Image |  |
| integer | X |  |
| integer | Y |  |
| linearcolor | Failure Color |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Valid |  |
| linearcolor | Return Value | Returns the color value for the given pixel. If the input position is invalid, the format is invalid,or the reference isn't set, bValid will be false and the function will return FailureColor. The coloris converted using the image's gamma space in to linear space.Do not use this for full image processing as it will be extremely slow, contact support if you need suchfunctionality. |
