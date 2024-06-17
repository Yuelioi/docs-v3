---
title: Push Widget
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Activatable Widget Stack](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ActivatableWidgetStack)

Adds a widget of the given class to the container.
Note that all widgets added to the container are pooled, so the caller should not try to cache and re-use the created widget.

It is possible for multiple instances of the same class to be added to the container at once, so any instance created in the past
is not guaranteed to be the one returned this time.

So in practice, you should not trust that any prior state has been retained on the returned widget, and establish all appropriate properties every time.

Target is Common Activatable Widget Container Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Activatable Widget Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a widget of the given class to the container.Note that all widgets added to the container are pooled, so the caller should not try to cache and re-use the created widget.It is possible for multiple instances of the same class to be added to the container at once, so any instance created in the pastis not guaranteed to be the one returned this time.So in practice, you should not trust that any prior state has been retained on the returned widget, and establish all appropriate properties every time. |
