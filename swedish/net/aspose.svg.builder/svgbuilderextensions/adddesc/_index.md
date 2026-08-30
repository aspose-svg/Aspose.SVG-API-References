---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddDesc-metod. Lägger till en desc-elementkonfiguration till byggaren. Desc-elementet används för att tillhandahålla en beskrivning för SVG-innehåll."
type: docs
weight: 110
url: /sv/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

Lägger till en 'desc'-elementkonfiguration till byggaren. 'desc'-elementet används för att tillhandahålla en beskrivning för SVG-innehåll.

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'desc'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
