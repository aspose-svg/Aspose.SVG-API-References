---
title: "SVGBuilderExtensions.OnWaiting"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnWaiting metod. Ställer in onwaiting‑händelseattributet för att hantera händelser när mediuppspelning fördröjs på grund av data‑buffering"
type: docs
weight: 1850
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onwaiting/
---
## SVGBuilderExtensions.OnWaiting<TBuilder> method

Ställer in 'onwaiting'-attributet för att hantera händelser när medieuppspelning fördröjs på grund av databuffring.

```csharp
public static TBuilder OnWaiting<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras när mediuppspelning fördröjs för buffring. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
