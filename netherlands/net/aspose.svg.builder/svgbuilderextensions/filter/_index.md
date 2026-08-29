---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Filter-methode. Stelt het filter‑attribuut in voor een SVG-element met behulp van een aangepaste configuratie."
type: docs
weight: 840
url: /nl/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

Stelt het 'filter' attribuut voor een SVG-element in met een aangepaste configuratie.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | Een delegate om de FilterValueListBuilder te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
