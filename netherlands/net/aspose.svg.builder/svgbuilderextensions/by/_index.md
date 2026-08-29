---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions By methode. Stelt het by-attribuut in dat de relatieve offsetwaarde voor de animatie definieert met een opgegeven lengtetype."
type: docs
weight: 620
url: /nl/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

Stelt het 'by' attribuut in, waarmee de relatieve offsetwaarde voor de animatie met een gespecificeerd lengtetype wordt gedefinieerd.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De relatieve offsetwaarde voor de animatie. |
| type | Het lengtetype voor de 'by' waarde. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
