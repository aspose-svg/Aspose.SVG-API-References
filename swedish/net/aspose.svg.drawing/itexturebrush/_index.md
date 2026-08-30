---
title: "ITextureBrush-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Drawing.ITextureBrush-gränssnitt. Definierar penselgränssnitt som använder en bild för att fylla insidan av en form."
type: docs
weight: 3520
url: /sv/net/aspose.svg.drawing/itexturebrush/
---
## ITextureBrush interface

Definierar penselgränssnitt som använder en bild för att fylla insidan av en form.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ColorMap](../../aspose.svg.drawing/itexturebrush/colormap/) { get; } | Antalet element måste vara jämnt. Varje jämnt element är den gamla färgen. Varje udda element är den nya färgen. |
| [Image](../../aspose.svg.drawing/itexturebrush/image/) { get; } | Hämtar eller anger bilden som används av penseln. |
| [ImageArea](../../aspose.svg.drawing/itexturebrush/imagearea/) { get; } | Anger den del av bilden som används av penseln. Om den är lika med RectangleF.Empty används hela bilden. Koordinaterna är i pixlar. |
| [Opacity](../../aspose.svg.drawing/itexturebrush/opacity/) { get; set; } | Hämta opacitetsvärde i en färgtransformationsmatris. |

### Se även

* interface [ITransformableBrush](../itransformablebrush/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
