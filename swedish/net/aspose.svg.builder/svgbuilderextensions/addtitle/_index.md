---
title: "SVGBuilderExtensions.AddTitle"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddTitle-metod. Lägger till en titel-elementkonfiguration till byggaren. Titel-elementet används för att tillhandahålla en titel för SVG-innehåll"
type: docs
weight: 540
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addtitle/
---
## SVGBuilderExtensions.AddTitle<TBuilder> method

Lägger till en 'title' elementkonfiguration till byggaren. 'title'-elementet används för att tillhandahålla en titel för SVG-innehåll.

```csharp
public static TBuilder AddTitle<TBuilder>(this TBuilder builder, 
    Action<SVGTitleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'title'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGTitleElementBuilder](../../svgtitleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
