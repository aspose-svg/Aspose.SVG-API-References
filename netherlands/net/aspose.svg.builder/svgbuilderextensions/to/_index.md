---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions To-methode. Stelt het to-attribuut in dat de eindwaarde van de animatie definieert met een opgegeven lengtetype"
type: docs
weight: 2250
url: /nl/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Stelt het 'to' attribuut in, waarbij de eindwaarde van de animatie met een gespecificeerd lengtetype wordt gedefinieerd.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De eindwaarde voor de animatie. |
| type | Het lengtetype voor de 'to'-waarde. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
