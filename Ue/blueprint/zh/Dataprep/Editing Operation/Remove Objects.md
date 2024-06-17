---
title: Remove Objects
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep) > [Editing Operation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep/EditingOperation)

Remove an array of objects from the Dataprep's and/or action's working set

Target is Dataprep Editing Operation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Objects | An array of objects to be removed from the working set |
| boolean | Local Context | If set to true, the object is removed from the current working set. The object will not be accessible to any subsequent operation using the current context. If set to false, the object is removed from the Dataprep's working set. The object will not be accessible to any subsequent operation in the Dataprep's pipeline. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
