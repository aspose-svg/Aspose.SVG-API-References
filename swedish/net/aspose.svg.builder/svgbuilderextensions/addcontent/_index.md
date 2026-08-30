---
title: "SVGBuilderExtensions.AddContent"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddContent‑metod. Lägger till textinnehåll i SVG‑elementet"
type: docs
weight: 90
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

Lägger till textinnehåll till SVG-elementet.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| text | Texten som ska läggas till i elementet. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod möjliggör att lägga till textinnehåll direkt i ett SVG‑element. Den är användbar för element som innehåller textdata.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
