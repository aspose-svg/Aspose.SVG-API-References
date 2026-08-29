---
title: "SVGBuilderExtensions.AddSvg"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddSvg‑methode. Voegt een svg‑scalable vector graphics‑elementconfiguratie toe aan de builder"
type: docs
weight: 500
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addsvg/
---
## SVGBuilderExtensions.AddSvg<TBuilder> method

Voegt een 'svg' (scalable vector graphics) elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddSvg<TBuilder>(this TBuilder builder, 
    Action<SVGSVGElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'svg'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGSVGElementBuilder](../../svgsvgelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
