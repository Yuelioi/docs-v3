---
title: Create and Host Cloud ARPin Latent Action
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Google ARCore Services](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GoogleARCoreServices) > [Cloud ARPin](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GoogleARCoreServices/CloudARPin)

This will start a Latent Action to host the ARPin and creating a UCloudARPin from it.
The complete flow of this Latent Action will be triggered if the hosting is complete
or an error has occurred.

Note that a UCloudARPin will be always created when this function is called, even in the case
that the CloudId is failed to host. You can check the CloudState of returning UCloudARPin
to see why the hosting failed.

Target is Google ARCore Services Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | ARPin to Host | The ARPin to host. |
| integer | Lifetime in Days | The lifetime of the cloud anchor in days. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| enum | Out Hosting Result | The ARPin hosting result. |
| object | Out Cloud ARPin | A new instance of UCloudARPin created using the input ARPinToHost. |
