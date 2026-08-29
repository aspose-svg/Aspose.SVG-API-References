---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions KeySplines-methode. Stelt het keySplines-attribuut in dat de controlepunten specificeert voor het tempo van de animatie."
type: docs
weight: 1060
url: /nl/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

Stelt het 'keySplines' attribuut in, waarbij de controlepunten voor de timing van de animatie worden gespecificeerd.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| buildSplines | De actie om de spline-configuratie te bouwen. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
