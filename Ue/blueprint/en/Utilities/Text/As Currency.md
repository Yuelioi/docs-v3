---
display_name: As Currency
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Text](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Text)

Generate an FText that represents the passed number as currency in the current culture.
BaseVal is specified in the smallest fractional value of the currency and will be converted for formatting according to the selected culture.
Keep in mind the CurrencyCode is completely independent of the culture it's displayed in (and they do not imply one another).
For example: FText::AsCurrencyBase(650, TEXT("EUR")); would return an FText of "6.50" in most English cultures (en_US/en_UK) and "6,50" in Spanish (es_ES) (where  is U+20AC)

Target is Kismet Text Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Base Value |  |
| string | Currency Code |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| text | Return Value | Generate an FText that represents the passed number as currency in the current culture.BaseVal is specified in the smallest fractional value of the currency and will be converted for formatting according to the selected culture.Keep in mind the CurrencyCode is completely independent of the culture it's displayed in (and they do not imply one another).For example: FText::AsCurrencyBase(650, TEXT("EUR")); would return an FText of "6.50" in most English cultures (en_US/en_UK) and "6,50" in Spanish (es_ES) (where  is U+20AC) |
