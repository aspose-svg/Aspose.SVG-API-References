---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddMetadata-metoden. Lägger till en metadata‑elementkonfiguration i byggaren. Metadata‑elementet används för att lägga till metadata i SVG‑innehåll."
type: docs
weight: 390
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Lägger till en 'metadata'-elementkonfiguration till byggaren. 'metadata'-elementet används för att lägga till metadata i SVG-innehåll.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| TElement | Typen som representerar 'metadata'-elementet i SVG-modellen. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'metadata'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
