---
display_name: Set Replicates
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Networking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Networking)

Set whether this actor replicates to network clients. When this actor is spawned on the server it will be sent to clients as well.
Properties flagged for replication will update on clients if they change on the server.
Internally changes the RemoteRole property and handles the cases where the actor needs to be added to the network actor list.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | In Replicates | Whether this Actor replicates to network clients. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
