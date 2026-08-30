---
title: "SVGBuilderExtensions.AddSet"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddSet‑metod. Lägger till en set‑elementkonfiguration till byggaren."
type: docs
weight: 470
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addset/
---
## SVGBuilderExtensions.AddSet<TBuilder> method

Lägger till en 'set'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddSet<TBuilder>(this TBuilder builder, 
    Action<SVGSetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'set'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGSetElementBuilder](../../svgsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
