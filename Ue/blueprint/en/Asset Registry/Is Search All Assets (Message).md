---
display_name: Is Search All Assets (Message)
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Whether SearchAllAssets has been called, or was auto-called at startup. When async (editor or cooking), if SearchAllAssets has ever been called,
any newly-mounted directory will be automatically searched.

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether SearchAllAssets has been called, or was auto-called at startup. When async (editor or cooking), if SearchAllAssets has ever been called,any newly-mounted directory will be automatically searched. |
