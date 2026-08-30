---
title: "SVGBuilderExtensions.AddAnimate"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddAnimate-metod. Lägger till en animate-elementkonfiguration till byggaren"
type: docs
weight: 30
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addanimate/
---
## SVGBuilderExtensions.AddAnimate<TBuilder> method

Lägger till en 'animate'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddAnimate<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'animate'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGAnimateElementBuilder](../../svganimateelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
