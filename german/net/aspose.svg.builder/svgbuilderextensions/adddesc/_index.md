---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddDesc-Methode. Fügt dem Builder eine desc-Elementkonfiguration hinzu. Das desc-Element wird verwendet, um eine Beschreibung für SVG-Inhalte bereitzustellen"
type: docs
weight: 110
url: /de/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

Fügt dem Builder eine 'desc'-Elementkonfiguration hinzu. Das 'desc'-Element wird verwendet, um eine Beschreibung für SVG-Inhalte bereitzustellen.

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'desc'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
