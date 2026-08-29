---
title: "SVGBuilderExtensions.From"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions From-methode. Stelt het from‑attribuut in dat de startwaarde van de animatie definieert met een opgegeven lengtetype"
type: docs
weight: 960
url: /nl/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

Stelt het 'from' attribuut in, waarmee de startwaarde van de animatie wordt gedefinieerd met een gespecificeerd lengtetype.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De startwaarde voor de animatie. |
| type | Het lengtetype voor de 'from'-waarde. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
