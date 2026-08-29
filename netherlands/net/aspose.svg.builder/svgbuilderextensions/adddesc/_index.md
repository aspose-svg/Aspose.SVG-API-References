---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddDesc-methode. Voegt een desc‑elementconfiguratie toe aan de builder. Het desc‑element wordt gebruikt om een beschrijving voor SVG-inhoud te geven."
type: docs
weight: 110
url: /nl/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

Voegt een 'desc'‑elementconfiguratie toe aan de builder. Het 'desc'‑element wordt gebruikt om een beschrijving voor SVG‑inhoud te geven.

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'desc'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
