---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddFeMerge-metod. Lägger till en feMerge‑elementkonfiguration i byggaren. Detta element möjliggör att filtereffekter appliceras samtidigt istället för sekventiellt"
type: docs
weight: 240
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Lägger till en 'feMerge'-elementkonfiguration till byggaren. Detta element möjliggör att filtereffekter tillämpas samtidigt istället för sekventiellt.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för elementet 'feMerge'. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
