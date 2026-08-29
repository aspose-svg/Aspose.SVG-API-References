---
title: "SVGBuilderExtensions.AddView"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddView-methode. Voegt een view-elementconfiguratie toe aan de builder"
type: docs
weight: 560
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addview/
---
## SVGBuilderExtensions.AddView<TBuilder> method

Voegt een 'view' elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddView<TBuilder>(this TBuilder builder, 
    Action<SVGViewElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'view'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGViewElementBuilder](../../svgviewelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
