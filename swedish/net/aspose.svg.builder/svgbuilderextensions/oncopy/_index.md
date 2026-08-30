---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnCopy metod. Ställer in oncopy‑händelseattributet som definierar ett skript som körs när innehåll kopieras från SVG‑elementet"
type: docs
weight: 1270
url: /sv/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

Ställer in händelseattributet 'oncopy' och definierar ett skript som körs när innehåll kopieras från SVG-elementet.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras vid kopieringshändelsen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
