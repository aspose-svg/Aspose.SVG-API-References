---
title: "SVGBuilderExtensions.AddTitle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddTitle-Methode. Fügt dem Builder eine Titel-Element-Konfiguration hinzu. Das Titel-Element wird verwendet, um einen Titel für SVG-Inhalte bereitzustellen."
type: docs
weight: 540
url: /de/net/aspose.svg.builder/svgbuilderextensions/addtitle/
---
## SVGBuilderExtensions.AddTitle<TBuilder> method

Fügt dem Builder eine Konfiguration für das 'title'-Element hinzu. Das 'title'-Element wird verwendet, um einen Titel für SVG-Inhalte bereitzustellen.

```csharp
public static TBuilder AddTitle<TBuilder>(this TBuilder builder, 
    Action<SVGTitleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'title'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGTitleElementBuilder](../../svgtitleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
