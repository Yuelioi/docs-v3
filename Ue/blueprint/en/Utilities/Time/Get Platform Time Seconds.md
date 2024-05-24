---
display_name: Get Platform Time Seconds
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Time](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Time)

Returns the current platform time in seconds. Not coupled to any gameplay or other containerization logic - this
function is useful for timing execution time or timestamping data. Marked as callable rather than pure because
implicit evaluation may be confusing, both for blueprint authors and blueprint readers. For implicit execution
simply wrap it in a blueprint pure function.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | Returns the current platform time in seconds. Not coupled to any gameplay or other containerization logic - thisfunction is useful for timing execution time or timestamping data. Marked as callable rather than pure becauseimplicit evaluation may be confusing, both for blueprint authors and blueprint readers. For implicit executionsimply wrap it in a blueprint pure function. |
