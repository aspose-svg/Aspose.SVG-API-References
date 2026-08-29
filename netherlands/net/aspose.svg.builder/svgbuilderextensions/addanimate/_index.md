---
title: "SVGBuilderExtensions.AddAnimate"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddAnimate-methode. Voegt een animate-elementconfiguratie toe aan de bouwer."
type: docs
weight: 30
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addanimate/
---
## SVGBuilderExtensions.AddAnimate<TBuilder> method

Voegt een 'animate'‑elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddAnimate<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie-actie voor het 'animate'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGAnimateElementBuilder](../../svganimateelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
