---
display_name: Generate PFM Extended
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Miscellaneous](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Miscellaneous) > [Warp](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Miscellaneous/Warp)

Generate and save data to a PFM file. Additionally, we have an array of tiles validiy flags (false == all pixels of a tile are NaN)

Target is Warp Utils Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | File |  |
| vector | Start Location |  |
| rotator | Start Rotation |  |
| object | PFMOrigin |  |
| integer | Tiles Horizontal |  |
| integer | Tiles Vertical |  |
| real | Column Angle |  |
| real | Tile Size Horizontal |  |
| real | Tile Size Vertical |  |
| integer | Tile Pixels Horizontal |  |
| integer | Tile Pixels Vertical |  |
| boolean | Add Margin |  |
| boolean | Tiles Validity Flags |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Generate and save data to a PFM file. Additionally, we have an array of tiles validiy flags (false == all pixels of a tile are NaN) |
