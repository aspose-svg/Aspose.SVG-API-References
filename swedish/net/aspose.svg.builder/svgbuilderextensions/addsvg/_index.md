---
title: "SVGBuilderExtensions.AddSvg"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddSvg-metod. Lägger till en konfiguration för ett svg scalable vector graphics‑element till byggaren."
type: docs
weight: 500
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addsvg/
---
## SVGBuilderExtensions.AddSvg<TBuilder> method

Lägger till en 'svg' (scalable vector graphics) elementkonfiguration till byggaren.

```csharp
public static TBuilder AddSvg<TBuilder>(this TBuilder builder, 
    Action<SVGSVGElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'svg'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGSVGElementBuilder](../../svgsvgelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
