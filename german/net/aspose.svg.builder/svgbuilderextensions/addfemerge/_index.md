---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddFeMerge-Methode. Fügt dem Builder eine feMerge-Elementkonfiguration hinzu. Dieses Element ermöglicht es, Filtereffekte gleichzeitig statt nacheinander anzuwenden."
type: docs
weight: 240
url: /de/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Fügt dem Builder eine 'feMerge'-Elementkonfiguration hinzu. Dieses Element ermöglicht es, Filtereffekte gleichzeitig statt nacheinander anzuwenden.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'feMerge'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
