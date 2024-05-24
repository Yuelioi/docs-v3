---
display_name: Initialize Scalar Parameter and Get Index
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Material](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Material)

Use this function to set an initial value and fetch the index for use in SetScalarParameterByIndex. This
function should only be called once for a particular name, and then use SetScalarParameterByIndex for subsequent
calls. However, beware using this except in cases where optimization is critical, which is generally only if
you're using an unusually high number of parameters in a material and setting a large number of parameters in the
same frame. Also, if the material is changed in any way that can change the parameter list, the index can be
invalidated.

Target is Material Instance Dynamic

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Parameter Name |  |
| real | Value |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Out Parameter Index |  |
| boolean | Return Value | Use this function to set an initial value and fetch the index for use in SetScalarParameterByIndex. Thisfunction should only be called once for a particular name, and then use SetScalarParameterByIndex for subsequentcalls. However, beware using this except in cases where optimization is critical, which is generally only ifyou're using an unusually high number of parameters in a material and setting a large number of parameters in thesame frame. Also, if the material is changed in any way that can change the parameter list, the index can beinvalidated. |
