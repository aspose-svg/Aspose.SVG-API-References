---
title: "SVGBuilderExtensions.AddMask"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddMask metod. Lägger till en mask-elementkonfiguration till byggaren"
type: docs
weight: 380
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addmask/
---
## SVGBuilderExtensions.AddMask<TBuilder> method

Lägger till en 'mask'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddMask<TBuilder>(this TBuilder builder, 
    Action<SVGMaskElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'mask'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGMaskElementBuilder](../../svgmaskelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
