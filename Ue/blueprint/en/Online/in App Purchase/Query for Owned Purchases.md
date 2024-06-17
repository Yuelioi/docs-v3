---
title: Query for Owned Purchases
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online) > [in App Purchase](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online/inAppPurchase)

Create Proxy Object for in App Purchase Query Owned

Target is In App Purchase Callback Proxy 2

Latent. This node will complete at a later time. Latent nodes can only be placed in event graphs.

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when there is a successful In-App Purchase transaction |
| exec | On Failure | Called when there is an unsuccessful In-App Purchase transaction |
| enum | Purchase Status |  |
| struct | In App Purchase Receipts |  |
