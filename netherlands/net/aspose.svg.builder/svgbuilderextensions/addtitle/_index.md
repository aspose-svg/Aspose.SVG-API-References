---
title: "SVGBuilderExtensions.AddTitle"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddTitle-methode. Voegt een titel‑elementconfiguratie toe aan de builder. Het titel‑element wordt gebruikt om een titel voor SVG‑inhoud te bieden."
type: docs
weight: 540
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addtitle/
---
## SVGBuilderExtensions.AddTitle<TBuilder> method

Voegt een 'title' elementconfiguratie toe aan de builder. Het 'title' element wordt gebruikt om een titel voor SVG-inhoud te geven.

```csharp
public static TBuilder AddTitle<TBuilder>(this TBuilder builder, 
    Action<SVGTitleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'title'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGTitleElementBuilder](../../svgtitleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
