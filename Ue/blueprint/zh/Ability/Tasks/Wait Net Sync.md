---
display_name: Wait Net Sync
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Synchronize execution flow between Client and Server. Depending on SyncType, the Client and Server will wait for the other to reach this node or another WaitNetSync node in the ability before continuing execution.

BothWait - Both Client and Server will wait until the other reaches the node. (Whoever gets their first, waits for the other before continueing).
OnlyServerWait - Only server will wait for the client signal. Client will signal and immediately continue without waiting to hear from Server.
OnlyClientWait - Only client will wait for the server signal. Server will signal and immediately continue without waiting to hear from Client.

Note that this is "ability instance wide". These sync points never affect sync points in other abilities.

In most cases you will have both client and server execution paths connected to the same WaitNetSync node. However it is possible to use separate nodes
for cleanliness of the graph. The "signal" is "ability instance wide".

Target is Ability Task Network Sync Point

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| enum | Sync Type |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Sync |  |
