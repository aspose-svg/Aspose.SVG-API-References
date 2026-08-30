---
title: "SVGBuilderExtensions.AddDefs"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddDefs-metoden. Lägger till en defs‑definitions‑elementkonfiguration till byggaren"
type: docs
weight: 100
url: /sv/net/aspose.svg.builder/svgbuilderextensions/adddefs/
---
## SVGBuilderExtensions.AddDefs<TBuilder> method

Lägger till en 'defs' (definitioner)-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddDefs<TBuilder>(this TBuilder builder, 
    Action<SVGDefsElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'defs'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGDefsElementBuilder](../../svgdefselementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
