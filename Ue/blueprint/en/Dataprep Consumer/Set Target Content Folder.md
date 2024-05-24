---
display_name: Set Target Content Folder
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep Consumer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataprepConsumer)

Sets the path of the package the consumer should move assets to if applicable.
Generally, this package path is substituted to the temporary path the assets are in

Target is Dataprep Content Consumer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Target Content Folder | : Path of the package to save any assets in |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| text | Out Failure Reason | : String explaining reason of failure to set the target content folder |
| boolean | Return Value | true if the assignment has been successful, false otherwise |
