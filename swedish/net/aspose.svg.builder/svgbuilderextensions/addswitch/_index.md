---
title: "SVGBuilderExtensions.AddSwitch"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddSwitch‑metoden. Lägger till en switch‑elementkonfiguration i byggaren."
type: docs
weight: 510
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addswitch/
---
## SVGBuilderExtensions.AddSwitch<TBuilder> method

Lägger till en 'switch' elementkonfiguration till byggaren.

```csharp
public static TBuilder AddSwitch<TBuilder>(this TBuilder builder, 
    Action<SVGSwitchElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'switch'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGSwitchElementBuilder](../../svgswitchelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
