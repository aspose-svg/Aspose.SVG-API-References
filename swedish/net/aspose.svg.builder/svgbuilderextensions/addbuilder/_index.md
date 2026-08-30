---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddBuilder-metoden. Lägger till en befintlig SVG‑elementbyggare till den aktuella SVG‑elementbyggaren. Denna metod används för att inkludera en fördefinierad SVG‑elementbyggare i den aktuella byggaren."
type: docs
weight: 60
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Lägger till en befintlig SVG-elementbyggare till den aktuella SVG-elementbyggaren. Denna metod används för att inkludera en fördefinierad SVG-elementbyggare i den aktuella byggaren.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| TElementBuilder | Typen av SVG‑elementbyggare som ska konfigureras. TElementBuilder måste implementera ISVGElementBuilder. |
| byggare | SVG‑elementbyggaren som den andra elementbyggaren läggs till. |
| elementBuilder | SVG‑elementbyggaren som ska läggas till. |

### Returvärde

Den ursprungliga SVG-elementbyggaren för metodkedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
