---
title: Get Oculus Identity
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Oculus](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus) > [Identity](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus/Identity)

Kick off GetOculusIdentity. Asynchronous-- see OnLoginCompleteDelegate for results.

Target is Oculus Identity Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Local User Num |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when it successfully gets back the oculus id |
| exec | On Failure | Called when it fails to get the oculus id |
| string | Oculus Id |  |
| string | Oculus Name |  |
