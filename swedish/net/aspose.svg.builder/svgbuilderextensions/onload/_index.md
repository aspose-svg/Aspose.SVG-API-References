---
title: "SVGBuilderExtensions.OnLoad"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnLoad-metoden. Ställer in onload‑attributet för att hantera laddningshändelser på elementet."
type: docs
weight: 1520
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onload/
---
## SVGBuilderExtensions.OnLoad<TBuilder> method

Ställer in 'onload'-händelseattributet för att hantera laddningshändelser på elementet.

```csharp
public static TBuilder OnLoad<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras när elementet har laddats färdigt. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
