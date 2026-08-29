---
title: "SVGBuilderExtensions.AddDefs"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddDefs-methode. Voegt een defs‑definitie‑elementconfiguratie toe aan de builder"
type: docs
weight: 100
url: /nl/net/aspose.svg.builder/svgbuilderextensions/adddefs/
---
## SVGBuilderExtensions.AddDefs<TBuilder> method

Voegt een 'defs' (definities)‑elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddDefs<TBuilder>(this TBuilder builder, 
    Action<SVGDefsElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'defs'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGDefsElementBuilder](../../svgdefselementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
