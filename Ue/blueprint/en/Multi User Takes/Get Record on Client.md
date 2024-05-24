---
display_name: Get Record on Client
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi User Takes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MultiUserTakes)

Gets the checkbox value in the "Record On Client" column in the settings displayed at the bottom of the "Take Recorder" tab.
This function queries the state of any connected client. For the local client, you can also use GetRecordOnClientLocal.

Target is Multi User Takes Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Client Endpoint Id | ID of the client. You can get this by using e.g.UMultiUserSubsystem::GetRemoteClientIds or UMultiUserSubsystem::GetLocalClientId. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value |  |
