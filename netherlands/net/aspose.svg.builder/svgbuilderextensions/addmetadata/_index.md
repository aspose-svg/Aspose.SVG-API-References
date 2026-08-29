---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddMetadata-methode. Voegt een metadata-elementconfiguratie toe aan de builder. Het metadata-element wordt gebruikt om metadata toe te voegen aan SVG-inhoud."
type: docs
weight: 390
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Voegt een 'metadata'-elementconfiguratie toe aan de builder. Het 'metadata'-element wordt gebruikt om metadata toe te voegen aan SVG-inhoud.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| TElement | Het type dat het 'metadata'-element in het SVG-model vertegenwoordigt. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'metadata'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
