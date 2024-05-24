---
display_name: Config Google ARCore Services
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Google ARCore Services](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GoogleARCoreServices) > [Configuration](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GoogleARCoreServices/Configuration)

Configure the current Unreal AR session with the desired GoogleARCoreServices configuration.
If there is an running AR session, the configuration will take effect immediately. Otherwise,
it will take effect when the next AR session is running.

Target is Google ARCore Services Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Service Config | The desired GoogleARCoreServices configuration. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if GoogleARCoreServices is configured successfully. False if the configuration failed to apply. |
