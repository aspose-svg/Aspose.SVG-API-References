---
title: "SVGBuilderExtensions.OnUnload"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnUnload-metoden. Ställer in onunload-händelseattributet som definierar ett skript att köra när SVG-dokumentet avlastas"
type: docs
weight: 1830
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onunload/
---
## SVGBuilderExtensions.OnUnload<TBuilder> method

Ställer in 'onunload'-attributet och definierar ett skript som körs när SVG-dokumentet laddas ur.

```csharp
public static TBuilder OnUnload<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript-funktionen eller skriptet som ska köras när dokumentet avlastas. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
