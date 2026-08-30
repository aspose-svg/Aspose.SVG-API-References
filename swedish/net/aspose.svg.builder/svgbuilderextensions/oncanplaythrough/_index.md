---
title: "SVGBuilderExtensions.OnCanPlayThrough"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnCanPlayThrough-metod. Ställer in oncanplaythrough‑händelseattributet för att hantera medieuppspelning utan avbrott"
type: docs
weight: 1230
url: /sv/net/aspose.svg.builder/svgbuilderextensions/oncanplaythrough/
---
## SVGBuilderExtensions.OnCanPlayThrough<TBuilder> method

Ställer in händelseattributet 'oncanplaythrough' för att hantera medias spelbarhet utan avbrott.

```csharp
public static TBuilder OnCanPlayThrough<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript-funktionen eller skriptet som ska köras när media kan spelas igenom till slutet utan att stoppas för buffring. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
