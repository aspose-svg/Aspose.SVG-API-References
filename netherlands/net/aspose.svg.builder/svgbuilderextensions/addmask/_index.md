---
title: "SVGBuilderExtensions.AddMask"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddMask methode. Voegt een mask‑elementconfiguratie toe aan de builder."
type: docs
weight: 380
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addmask/
---
## SVGBuilderExtensions.AddMask<TBuilder> method

Voegt een 'mask'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddMask<TBuilder>(this TBuilder builder, 
    Action<SVGMaskElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'mask'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGMaskElementBuilder](../../svgmaskelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
