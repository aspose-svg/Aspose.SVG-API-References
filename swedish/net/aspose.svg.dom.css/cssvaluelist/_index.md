---
title: "CSSValueList-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.CSSValueList-klass. CSSValueList-gränssnittet ger abstraktionen av en ordnad samling av CSS-värden."
type: docs
weight: 2500
url: /sv/net/aspose.svg.dom.css/cssvaluelist/
---
## CSSValueList class

CSSValueList-gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑värden.

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Initierar en ny instans av klassen `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | Initierar en ny instans av klassen `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | Initierar en ny instans av klassen `CSSValueList`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [CSSText](../../aspose.svg.dom.css/cssvaluelist/csstext/) { get; set; } | CSSText-egenskapen i [`CSSValue`](../cssvalue/)-gränssnittet representerar det aktuella beräknade CSS-egenskapsvärdet. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | En kod som definierar värdets typ. |
| [Item](../../aspose.svg.dom.css/cssvaluelist/item/) { get; } | Hämtar [`CSSValue`](../cssvalue/) på det angivna indexet. |
| [Length](../../aspose.svg.dom.css/cssvaluelist/length/) { get; } | Length‑egenskapen (skrivskyddad) i CSSValueList-gränssnittet representerar antalet CSSValues i listan. Intervallet av giltiga indexvärden är 0 till length‑1 inklusive. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bestämmer om det angivna Object är lika med den här instansen. |
| [GetEnumerator](../../aspose.svg.dom.css/cssvaluelist/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Returnerar en hashkod för den här instansen. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvaluelist/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objekttyp. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Returnerar en sträng som representerar den här instansen. |

### Se även

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
