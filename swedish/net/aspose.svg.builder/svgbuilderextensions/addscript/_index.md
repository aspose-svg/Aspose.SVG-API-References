---
title: "SVGBuilderExtensions.AddScript"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddScript‑metod. Lägger till en skript‑elementkonfiguration i byggaren"
type: docs
weight: 460
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addscript/
---
## SVGBuilderExtensions.AddScript<TBuilder> method

Lägger till en 'script'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddScript<TBuilder>(this TBuilder builder, 
    Action<SVGScriptElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'script'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGScriptElementBuilder](../../svgscriptelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
