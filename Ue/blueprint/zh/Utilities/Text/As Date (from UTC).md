---
display_name: As Date (from UTC)
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Text](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Text)

Converts a passed in date & time to a text, formatted as a date using the given timezone (default is the local timezone). This will convert the given date & time from UTC to the given timezone (taking into account DST).

Target is Kismet Text Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | In Date Time |  |
| string | In Time Zone |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| text | Return Value | Converts a passed in date & time to a text, formatted as a date using the given timezone (default is the local timezone). This will convert the given date & time from UTC to the given timezone (taking into account DST). |
