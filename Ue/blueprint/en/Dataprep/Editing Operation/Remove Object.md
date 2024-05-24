---
display_name: Remove Object
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep) > [Editing Operation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep/EditingOperation)

Remove an object from the Dataprep's and/or action's working set

Target is Dataprep Editing Operation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Object | Object to be removed from the working set |
| boolean | Local Context | If set to true, the object is removed from the current working set. The object will not be accessible to any subsequent operation using the current context. If set to false, the object is removed from the Dataprep's working set. The object will not be accessible to any subsequent operation in the Dataprep's pipeline. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
