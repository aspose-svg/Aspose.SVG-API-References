---
title: "SVGBuilderExtensions.AddClipPath"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddClipPath-methode. Voegt een clipPath-elementconfiguratie toe aan de builder"
type: docs
weight: 80
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addclippath/
---
## SVGBuilderExtensions.AddClipPath<TBuilder> method

Voegt een 'clipPath'‑elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddClipPath<TBuilder>(this TBuilder builder, 
    Action<SVGClipPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'clipPath'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGClipPathElementBuilder](../../svgclippathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
