---
display_name: Add Expected Log Error
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Automation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Automation)

Mute the report of log error and warning matching a pattern during an automated test. Treat the pattern as regex by default.

Target is Automation Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Expected Pattern String | Expects a Regex pattern. |
| integer | Occurrences |  |
| boolean | Exact Match |  |
| boolean | Is Regex |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
