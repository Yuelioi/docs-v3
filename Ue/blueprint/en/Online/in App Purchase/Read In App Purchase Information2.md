---
display_name: Read In App Purchase Information2
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online) > [in App Purchase](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online/inAppPurchase)

Queries a InAppPurchase for an integer value

Target is In App Purchase Query Callback Proxy 2

Latent. This node will complete at a later time. Latent nodes can only be placed in event graphs.

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| string | Product Identifiers |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when there is a successful InAppPurchase query |
| exec | On Failure | Called when there is an unsuccessful InAppPurchase query |
| struct | In App Offer Information |  |
