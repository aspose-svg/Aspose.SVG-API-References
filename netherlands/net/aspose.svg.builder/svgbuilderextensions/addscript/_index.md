---
title: "SVGBuilderExtensions.AddScript"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddScript-methode. Voegt een script‑elementconfiguratie toe aan de builder."
type: docs
weight: 460
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addscript/
---
## SVGBuilderExtensions.AddScript<TBuilder> method

Voegt een 'script' elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddScript<TBuilder>(this TBuilder builder, 
    Action<SVGScriptElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'script'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGScriptElementBuilder](../../svgscriptelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
