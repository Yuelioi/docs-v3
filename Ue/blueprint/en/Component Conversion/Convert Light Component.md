---
display_name: Convert Light Component
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Component Conversion](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ComponentConversion)

Note: We use FLT_MAX on these functions because Usd.TimeCode.Default().GetValue() is actually a nan, and nan arguments are automatically
sanitized to 0.0f. We manually convert the FLT_MAX value into Usd.TimeCode.Default().GetValue() within the functions though, so if you want the
Default timecode just omit the argument We are also forced to copypaste the FLT_MAX value (3.402823466e+38F) in here as the default arguments
are parsed before the preprocessor replaces the defines

Target is Usd Conversion Blueprint Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Component |  |
| string | Prim Path |  |
| real | Time Code |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Note: We use FLT_MAX on these functions because Usd.TimeCode.Default().GetValue() is actually a nan, and nan arguments are automaticallysanitized to 0.0f. We manually convert the FLT_MAX value into Usd.TimeCode.Default().GetValue() within the functions though, so if you want theDefault timecode just omit the argument We are also forced to copypaste the FLT_MAX value (3.402823466e+38F) in here as the default argumentsare parsed before the preprocessor replaces the defines |
