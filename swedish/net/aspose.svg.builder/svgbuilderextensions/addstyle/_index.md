---
title: "SVGBuilderExtensions.AddStyle"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddStyle-metoden. Lägger till en stil-elementkonfiguration till byggaren"
type: docs
weight: 490
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addstyle/
---
## SVGBuilderExtensions.AddStyle<TBuilder> method

Lägger till en 'style'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddStyle<TBuilder>(this TBuilder builder, 
    Action<SVGStyleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'style'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGStyleElementBuilder](../../svgstyleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
