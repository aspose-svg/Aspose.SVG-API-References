---
title: "SVGBuilderExtensions.OnCancel"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnCancel‑metod. Ställer in oncancel‑händelseattributet för att hantera användarens avbokningsåtgärder."
type: docs
weight: 1210
url: /sv/net/aspose.svg.builder/svgbuilderextensions/oncancel/
---
## SVGBuilderExtensions.OnCancel<TBuilder> method

Ställer in händelseattributet 'oncancel' för att hantera användarens avbokningsåtgärder.

```csharp
public static TBuilder OnCancel<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras vid avbokningshändelser. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
