---
display_name: Get Pixel Value
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Shared Image](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SharedImage)

Returns the value in the texture for the given pixel as a float vector. If the input position is invalid, the format is invalid,
or the reference isn't set, bValid will be false and the function will return FVector4(0,0,0,0).

Pixel values are directly returned with no gamma transformation to allow for lookup tables. Also note that
8 bit formats that you might normally expect to be normalized to 0..1 will return their values directly as 0..256.

This supports all image formats.

G8 is replicated to X/Y/Z/1.
R16/R32 is returned as R/0/0/1.

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

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Valid |  |
| struct | Return Value | Returns the value in the texture for the given pixel as a float vector. If the input position is invalid, the format is invalid,or the reference isn't set, bValid will be false and the function will return FVector4(0,0,0,0).Pixel values are directly returned with no gamma transformation to allow for lookup tables. Also note that8 bit formats that you might normally expect to be normalized to 0..1 will return their values directly as 0..256.This supports all image formats.G8 is replicated to X/Y/Z/1.R16/R32 is returned as R/0/0/1.Do not use this for full image processing as it will be extremely slow, contact support if you need suchfunctionality. |
