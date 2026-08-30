---
title: "TypeInfo klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.TypeInfo klass. TypeInfo representerar en typ som refereras från Element- eller Attr-noder som specificeras i scheman som är associerade med dokumentet"
type: docs
weight: 3280
url: /sv/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

TypeInfo representerar en typ som refereras från Element‑ eller Attr‑noder, specificerad i de scheman som är kopplade till dokumentet.

```csharp
public class TypeInfo : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename/) { get; } | Namnet på en typ som deklarerats för det associerade elementet eller attributet, eller null om okänt. |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace/) { get; } | Hämtar typens namnrymd. Namnrymden för den typ som deklarerats för det associerade elementet eller attributet eller null om elementet saknar deklaration eller om ingen namnrymdsinformation är tillgänglig. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom/)(*string, string, ulong*) | Denna metod returnerar om det finns en härledning mellan referenstypdefinitionen, d.v.s. TypeInfo som metoden anropas på, och den andra typdefinitionen, d.v.s. den som skickas som parameter. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension/) | Om dokumentets schema är ett XML-schema [XML Schema Part 1] representerar denna konstant härledningen genom utökning. |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list/) | Om dokumentets schema är ett XML-schema [XML Schema Part 1] representerar denna konstant listan. |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction/) | Om dokumentets schema är ett XML-schema [XML Schema Part 1], representerar denna konstant derivationen genom restriktion om komplexa typer är involverade, eller en restriktion om enkla typer är involverade. |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union/) | Om dokumentets schema är ett XML-schema [XML Schema Part 1], representerar denna konstant unionen om enkla typer är involverade. |

### Se även

* class [DOMObject](../domobject/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
