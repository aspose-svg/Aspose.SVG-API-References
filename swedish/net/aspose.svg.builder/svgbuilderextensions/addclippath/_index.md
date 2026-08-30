---
title: "SVGBuilderExtensions.AddClipPath"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddClipPath‑metod. Lägger till en clipPath‑elementkonfiguration i byggaren."
type: docs
weight: 80
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addclippath/
---
## SVGBuilderExtensions.AddClipPath<TBuilder> method

Lägger till en 'clipPath'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddClipPath<TBuilder>(this TBuilder builder, 
    Action<SVGClipPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'clipPath'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGClipPathElementBuilder](../../svgclippathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
