---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions SetPreserveAspectRatio method. Stelt het preserveAspectRatio‑attribuut in voor een SVG‑element."
type: docs
weight: 2020
url: /nl/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

Stelt het 'preserveAspectRatio' attribuut in voor een SVG-element.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| align | De uitlijningsinstelling voor de beeldverhouding. |
| meetOrSlice | Specificeert hoe een beeldverhouding wordt behouden (standaard is 'Meet'). |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
