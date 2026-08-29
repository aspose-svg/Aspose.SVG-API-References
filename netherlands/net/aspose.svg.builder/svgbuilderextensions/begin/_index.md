---
title: "SVGBuilderExtensions.Begin"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Begin-methode. Stelt het begin‑attribuut in dat bepaalt wanneer de animatie moet starten"
type: docs
weight: 610
url: /nl/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

Stelt het 'begin' attribuut in, waarmee wordt gedefinieerd wanneer de animatie moet starten.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
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
