---
display_name: Get Available Providers
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Live Link](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LiveLink)

- Broadcasts a message to the network and returns a list of all providers who replied within a set amount of time.

Target is Live Link Message Bus Finder

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Duration | The amount of time to wait for replies in seconds |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| struct | Available Providers | Will contain the collection of found Message Bus Providers. * |
