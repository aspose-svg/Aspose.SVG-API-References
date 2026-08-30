---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.SVG för .NET API-referens"
description: "TypeInfo IsDerivedFrom method. Denna metod returnerar om det finns en härledning mellan referenstypdefinitionen, dvs. den TypeInfo som metoden anropas på, och den andra typdefinitionen, dvs. den som skickas som parameter"
type: docs
weight: 30
url: /sv/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Denna metod returnerar om det finns en härledning mellan referenstypdefinitionen, d.v.s. TypeInfo som metoden anropas på, och den andra typdefinitionen, d.v.s. den som skickas som parameter.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeNamespaceArg | String | namnutrymmet för den andra typdefinitionen |
| typeNameArg | String | namnet på den andra typdefinitionen. |
| derivationMethod | UInt64 | typen av härledning och villkor som tillämpas mellan två typer, enligt listan med konstanter som tillhandahålls i detta gränssnitt. |

### Returvärde

Om dokumentets schema är en DTD eller inget schema är associerat med dokumentet kommer denna metod alltid att returnera false. Om dokumentets schema är ett XML-schema kommer metoden att returnera true om referenstypdefinitionen är härledd från den andra typdefinitionen enligt derivationsparametern. Om parametervärdet är 0 (ingen bit är satt till 1 för derivationMethod‑parametern) kommer metoden att returnera true om den andra typdefinitionen kan nås genom att rekursivt gå igenom någon kombination av {bas typdefinition}, {item typdefinition} eller {medlemstypdefinitioner} från referenstypdefinitionen.

### Se även

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
