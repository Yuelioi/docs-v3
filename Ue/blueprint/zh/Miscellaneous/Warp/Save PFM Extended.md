---
display_name: Save PFM Extended
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Miscellaneous](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Miscellaneous) > [Warp](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Miscellaneous/Warp)

Save data to a PFM file. Since the float NaN value is not available in blueprints, we provide a flags array (false == NaN)

Target is Warp Utils Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | File |  |
| integer | Tex Width |  |
| integer | Tex Height |  |
| vector | Vertices |  |
| boolean | Tiles Validity Flags |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Save data to a PFM file. Since the float NaN value is not available in blueprints, we provide a flags array (false == NaN) |
