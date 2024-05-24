---
display_name: Force Layout Prepass
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget)

Forces a pre-pass. A pre-pass caches the desired size of the widget hierarchy owned by this widget.
One pre-pass already happens for every widget before Tick occurs. You only need to perform another
pre-pass if you are adding child widgets this frame and want them to immediately be visible this frame.

Target is Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
