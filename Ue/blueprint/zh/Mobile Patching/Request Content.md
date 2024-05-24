---
display_name: Request Content
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mobile Patching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MobilePatching)

Attempt to download manifest file using specified manifest URL.
On success it will return an object that represents remote content. This object can be queried for additional information, like total content size, download size, etc.
User can choose to download and install remote content.

Target is Mobile Patching Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Remote Manifest URL | : URL from where manifest file can be downloaded. (http://my-server.com/awesomecontent.manifest) |
| string | Cloud URL | : URL from where content chunk data can be downloaded. (http://my-server.com/awesomecontent/clouddir) |
| string | Install Directory |  |
| delegate | On Succeeded |  |
| delegate | On Failed |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
