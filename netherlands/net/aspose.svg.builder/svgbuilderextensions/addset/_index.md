---
title: "SVGBuilderExtensions.AddSet"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddSet-methode. Voegt een set‑elementconfiguratie toe aan de builder."
type: docs
weight: 470
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addset/
---
## SVGBuilderExtensions.AddSet<TBuilder> method

Voegt een 'set' elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddSet<TBuilder>(this TBuilder builder, 
    Action<SVGSetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'set'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGSetElementBuilder](../../svgsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
