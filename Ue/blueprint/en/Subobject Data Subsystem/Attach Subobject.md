---
display_name: Attach Subobject
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Subobject Data Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SubobjectDataSubsystem)

Add the given subobject to a new owner. This will remove the subobject from its previous
owner if necessary.

Target is Subobject Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Owner Handle | The new owner to attach to |
| struct | Child to Add Handle | Handle to the subobject that will become a child of the owner |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the child was added successfully |
