---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions TextDecoration-metoden. Ställer in text-decoration-attributet för ett SVG-element som definierar dekorationer som läggs till i texten."
type: docs
weight: 2210
url: /sv/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Ställer in attributet 'text-decoration' för ett SVG-element, som definierar dekorationer som läggs till texten.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| underline | Anger om texten ska vara understruken. |
| overline | Anger om texten ska ha en överlinje. |
| lineThrough | Anger om texten ska ha en genomstrykning. |
| blink | Anger om texten ska blinka (rekommenderas inte att använda). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
