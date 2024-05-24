---
display_name: Get Triangle List Item
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [List Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/ListUtils)

Returns the integer triplet associated with the index Triangle in the Triangle List.
If Triangle is not valid for this Triangle List, the triplet (-1, -1, -1) will be returned and bIsValidIndex set to false.

Target is Geometry Script Library List Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Triangle List |  |
| integer | Triangle |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Triangle |  |
| struct | Return Value | Returns the integer triplet associated with the index Triangle in the Triangle List.If Triangle is not valid for this Triangle List, the triplet (-1, -1, -1) will be returned and bIsValidIndex set to false. |
