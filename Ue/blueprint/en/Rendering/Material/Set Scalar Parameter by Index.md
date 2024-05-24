---
display_name: Set Scalar Parameter by Index
order: 55
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Material](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Material)

Use the cached value of OutParameterIndex from InitializeScalarParameterAndGetIndex to set the scalar parameter
ONLY on the exact same MID. Do NOT presume the index can be used from one instance on another. Only use this
pair of functions when optimization is critical; otherwise use either SetScalarParameterValueByInfo or
SetScalarParameterValue.

Target is Material Instance Dynamic

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Parameter Index |  |
| real | Value |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Use the cached value of OutParameterIndex from InitializeScalarParameterAndGetIndex to set the scalar parameterONLY on the exact same MID. Do NOT presume the index can be used from one instance on another. Only use thispair of functions when optimization is critical; otherwise use either SetScalarParameterValueByInfo orSetScalarParameterValue. |
