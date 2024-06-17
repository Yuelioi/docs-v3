---
title: Verify Entitlement
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Oculus](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus) > [Entitlement](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus/Entitlement)

Kick off entitlement check. Asynchronous-- see OnUserPrivilegeCompleteDelegate for results.

Target is Oculus Entitlement Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when there is a successful entitlement check |
| exec | On Failure | Called when there is an unsuccessful entitlement check |
