---
title: "SVGBuilderExtensions.AddSymbol"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddSymbol‑metoden. Lägger till en symbol‑elementkonfiguration i byggaren."
type: docs
weight: 520
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addsymbol/
---
## SVGBuilderExtensions.AddSymbol<TBuilder> method

Lägger till en 'symbol' elementkonfiguration till byggaren.

```csharp
public static TBuilder AddSymbol<TBuilder>(this TBuilder builder, 
    Action<SVGSymbolElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'symbol'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGSymbolElementBuilder](../../svgsymbolelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
