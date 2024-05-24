---
display_name: Matches Any Tags
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayTags)

Determine if TagOne matches against any tag in OtherContainer

Target is Blueprint Gameplay Tag Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Tag One | Tag to check for match |
| struct | Other Container | Container to check against. |
| boolean | Exact Match | If true, the tag has to be exactly present, if false then TagOne will include it's parent tags while matching |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if TagOne matches any tags explicitly present in OtherContainer |
