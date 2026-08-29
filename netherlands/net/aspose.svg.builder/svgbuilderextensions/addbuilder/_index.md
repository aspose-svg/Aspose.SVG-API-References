---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddBuilder-methode. Voegt een bestaande SVG-elementbuilder toe aan de huidige SVG-elementbuilder. Deze methode wordt gebruikt om een vooraf gedefinieerde SVG-elementbuilder op te nemen in de huidige builder"
type: docs
weight: 60
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Voegt een bestaande SVG‑elementbuilder toe aan de huidige SVG‑elementbuilder. Deze methode wordt gebruikt om een vooraf gedefinieerde SVG‑elementbuilder in de huidige builder op te nemen.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| TElementBuilder | Het type van de SVG-elementbuilder dat moet worden geconfigureerd. TElementBuilder moet ISVGElementBuilder implementeren. |
| builder | De SVG-elementbuilder waaraan de andere elementbuilder wordt toegevoegd. |
| elementBuilder | De SVG-elementbouwer die moet worden toegevoegd. |

### Retourwaarde

De oorspronkelijke SVG-elementbuilder voor method chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
