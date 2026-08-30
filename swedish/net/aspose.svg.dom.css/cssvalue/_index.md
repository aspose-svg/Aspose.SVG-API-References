---
title: "CSSValue-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.CSSValue klass. Representerar ett enkelt eller komplext värde. Ett CSSValue-objekt förekommer endast i ett sammanhang av en CSS-egenskap."
type: docs
weight: 2490
url: /sv/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

Representerar ett enkelt eller komplext värde. Ett CSSValue‑objekt förekommer endast i samband med en CSS‑egenskap.

```csharp
public abstract class CSSValue : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | CSSText-egenskapen i `CSSValue`-gränssnittet representerar det aktuella beräknade CSS-egenskapsvärdet. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | En kod som definierar värdets typ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bestämmer om det angivna Object är lika med den här instansen. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Returnerar en hashkod för den här instansen. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objekttyp. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Returnerar en sträng som representerar den här instansen. |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality/) | Implementerar operatorn ==. |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality/) | Implementerar operatorn !=. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom/) | Värdet är ett anpassat värde. |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit/) | Värdet är ärvt och cssText innehåller "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value/) | Värdet är ett primitivt värde och en instans av gränssnittet CSSPrimitiveValue kan erhållas genom att använda bindningsspecifika kastmetoder på denna instans av gränssnittet CSSValue. |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list/) | Värdet är en CSSValue-lista och en instans av gränssnittet CSSValueList kan erhållas genom att använda bindningsspecifika kastmetoder på denna instans av gränssnittet CSSValue. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
