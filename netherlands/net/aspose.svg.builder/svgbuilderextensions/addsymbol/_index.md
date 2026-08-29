---
title: "SVGBuilderExtensions.AddSymbol"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddSymbol-methode. Voegt een symbool‑elementconfiguratie toe aan de builder"
type: docs
weight: 520
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addsymbol/
---
## SVGBuilderExtensions.AddSymbol<TBuilder> method

Voegt een 'symbol' elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddSymbol<TBuilder>(this TBuilder builder, 
    Action<SVGSymbolElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'symbol'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGSymbolElementBuilder](../../svgsymbolelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
