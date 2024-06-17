---
title: Should Open Due to Click
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Menu Anchor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MenuAnchor)

Returns true if we should open the menu due to a click. Sometimes we should not, if
the same MouseDownEvent that just closed the menu is about to re-open it because it
happens to land on the button.

Target is Menu Anchor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if we should open the menu due to a click. Sometimes we should not, ifthe same MouseDownEvent that just closed the menu is about to re-open it because ithappens to land on the button. |
