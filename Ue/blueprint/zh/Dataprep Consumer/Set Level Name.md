---
display_name: Set Level Name
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep Consumer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataprepConsumer)

Sets the name of the level the consumer should move objects to if applicable.

Target is Dataprep Content Consumer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Level Name | : New name for the consumer's level. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| text | Out Failure Reason | : String explaining reason of failure to set the level name |
| boolean | Return Value | true if the name has been successfully set |
