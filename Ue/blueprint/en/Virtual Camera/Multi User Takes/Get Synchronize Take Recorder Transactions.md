---
display_name: Get Synchronize Take Recorder Transactions
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera) > [Multi User Takes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera/MultiUserTakes)

Gets the value of the "SynchronizeTakeRecorderTransactions" checkbox in the settings displayed at the bottom of the "Take Recorder" tab.
This function queries the state of any connected client. For the local client, you can also use GetSynchronizeTakeRecorderTransactionsLocal.

Target is Multi User Takes VCam Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Client Endpoint Id | ID of the client. You can get this by using e.g.UMultiUserSubsystem::GetRemoteClientIds or UMultiUserSubsystem::GetLocalClientId. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value |  |
