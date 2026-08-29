---
title: "SVGBuilderExtensions.AddStyle"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddStyle-methode. Voegt een stijl‑elementconfiguratie toe aan de builder"
type: docs
weight: 490
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addstyle/
---
## SVGBuilderExtensions.AddStyle<TBuilder> method

Voegt een 'style' elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddStyle<TBuilder>(this TBuilder builder, 
    Action<SVGStyleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'style'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGStyleElementBuilder](../../svgstyleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
