---
title: "SVGBuilderExtensions.AddView"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddView metod. Lägger till en vy‑elementkonfiguration till byggaren"
type: docs
weight: 560
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addview/
---
## SVGBuilderExtensions.AddView<TBuilder> method

Lägger till en 'view' elementkonfiguration till byggaren.

```csharp
public static TBuilder AddView<TBuilder>(this TBuilder builder, 
    Action<SVGViewElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'view'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGViewElementBuilder](../../svgviewelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
