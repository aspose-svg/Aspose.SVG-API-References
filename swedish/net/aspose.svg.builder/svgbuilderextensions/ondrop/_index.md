---
title: "SVGBuilderExtensions.OnDrop"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnDrop-metod. Ställer in ondrop‑händelseattributet för att hantera att ett objekt släpps på ett giltigt mål för släpp."
type: docs
weight: 1380
url: /sv/net/aspose.svg.builder/svgbuilderextensions/ondrop/
---
## SVGBuilderExtensions.OnDrop<TBuilder> method

Ställer in 'ondrop'-händelseattributet för att hantera när ett objekt släpps på ett giltigt släppmål.

```csharp
public static TBuilder OnDrop<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript-funktionen eller skriptet som ska köras när ett objekt släpps på ett giltigt mål för släpp. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
