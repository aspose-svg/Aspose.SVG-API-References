---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddFeMerge-methode. Voegt een feMerge-elementconfiguratie toe aan de builder. Dit element maakt het mogelijk filtereffecten gelijktijdig toe te passen in plaats van opeenvolgend."
type: docs
weight: 240
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Voegt een configuratie van het 'feMerge'-element toe aan de builder. Dit element maakt het mogelijk filtereffecten gelijktijdig in plaats van opeenvolgend toe te passen.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'feMerge'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
