---
title: "SVGBuilderExtensions.AddMarker"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddMarker-metoden. Lägger till en markör-elementkonfiguration till byggaren"
type: docs
weight: 370
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addmarker/
---
## SVGBuilderExtensions.AddMarker<TBuilder> method

Lägger till en 'marker'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddMarker<TBuilder>(this TBuilder builder, 
    Action<SVGMarkerElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'marker'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGMarkerElementBuilder](../../svgmarkerelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
