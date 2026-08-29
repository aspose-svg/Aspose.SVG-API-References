---
title: "SVGBuilderExtensions.End"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions End-methode. Stelt het end-attribuut in dat bepaalt wanneer de animatie moet eindigen."
type: docs
weight: 790
url: /nl/net/aspose.svg.builder/svgbuilderextensions/end/
---
## SVGBuilderExtensions.End<TBuilder> method

Stelt het 'end' attribuut in, waarmee wordt gedefinieerd wanneer de animatie moet eindigen.

```csharp
public static TBuilder End<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| configureren | Een delegate om de timingwaarde te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
