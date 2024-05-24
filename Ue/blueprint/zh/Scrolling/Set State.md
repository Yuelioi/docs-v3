---
display_name: Set State
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scrolling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Scrolling)

Set the offset and size of the track's thumb.
Note that the maximum offset is 1.0-ThumbSizeFraction.
If the user can view 1/3 of the items in a single page, the maximum offset will be ~0.667f

Target is Scroll Bar

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | In Offset Fraction | Offset of the thumbnail from the top as a fraction of the total available scroll space. |
| real | In Thumb Size Fraction | Size of thumbnail as a fraction of the total available scroll space. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
