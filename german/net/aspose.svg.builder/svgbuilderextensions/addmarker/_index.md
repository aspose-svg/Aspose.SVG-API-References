---
title: "SVGBuilderExtensions.AddMarker"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddMarker-Methode. Fügt dem Builder eine Marker-Elementkonfiguration hinzu."
type: docs
weight: 370
url: /de/net/aspose.svg.builder/svgbuilderextensions/addmarker/
---
## SVGBuilderExtensions.AddMarker<TBuilder> method

Fügt dem Builder eine 'marker'-Elementkonfiguration hinzu.

```csharp
public static TBuilder AddMarker<TBuilder>(this TBuilder builder, 
    Action<SVGMarkerElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'marker'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGMarkerElementBuilder](../../svgmarkerelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
