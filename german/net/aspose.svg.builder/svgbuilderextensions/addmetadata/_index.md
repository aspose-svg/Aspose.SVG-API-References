---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddMetadata-Methode. Fügt dem Builder eine Konfiguration für ein metadata-Element hinzu. Das metadata-Element wird verwendet, um Metadaten zum SVG-Inhalt hinzuzufügen."
type: docs
weight: 390
url: /de/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Fügt dem Builder eine Konfiguration für das 'metadata'-Element hinzu. Das 'metadata'-Element wird verwendet, um Metadaten zum SVG-Inhalt hinzuzufügen.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| TElement | Der Typ, der das 'metadata'-Element im SVG-Modell repräsentiert. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'metadata'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
