---
title: "SVGBuilderExtensions.AddAnimateTransform"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddAnimateTransform-metoden. Lägger till en animateTransform-elementkonfiguration i byggaren"
type: docs
weight: 50
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addanimatetransform/
---
## SVGBuilderExtensions.AddAnimateTransform<TBuilder> method

Lägger till en 'animateTransform'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddAnimateTransform<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateTransformElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'animateTransform'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGAnimateTransformElementBuilder](../../svganimatetransformelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
