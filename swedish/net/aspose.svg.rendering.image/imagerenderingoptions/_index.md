---
title: "ImageRenderingOptions-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Rendering.Image.ImageRenderingOptions class. Representerar renderingsalternativ för ImageDevice. Detta alternativ används för att ange utdataformat för bild, komprimering, upplösning osv."
type: docs
weight: 4940
url: /sv/net/aspose.svg.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Representerar renderingsalternativ för [`ImageDevice`](../imagedevice/). Detta alternativ används för att ange utdataformat för bild, komprimering, upplösning osv.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initierar en ny instans av klassen `ImageRenderingOptions`; Png kommer att användas som standard bildformat. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | Initierar en ny instans av klassen `ImageRenderingOptions` med angivet bildformat. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | Hämtar eller anger färg som kommer att fylla bakgrunden på varje sida. Standardvärdet är Transparent. |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Ställer in eller hämtar Tagged Image File Format (TIFF) [`Compression`](../compression/). Som standard är denna egenskap LZW. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | Hämtar ett [`CssOptions`](../../aspose.svg.rendering/cssoptions/)‑objekt som används för konfiguration av bearbetning av CSS‑egenskaper. |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | Ställer in eller hämtar [`ImageFormat`](../imageformat/). Som standard är denna egenskap Png. |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Anger eller hämtar horisontell upplösning för utdata‑ och interna (som används under filterbehandling) bilder, i pixlar per tum. Standardvärdet för denna egenskap är 300 dpi. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | Hämtar ett sidinställningsobjekt som används för konfiguration av utdata siduppsättning. |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | Hämtar ett [`TextOptions`](../textoptions/)‑objekt som används för konfiguration av textrendering. |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | Anger om antialiasing ska användas. Som standard är antialiasing aktiverat. |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Anger eller hämtar vertikal upplösning för utdata‑ och interna (som används under filterbehandling) bilder, i pixlar per tum. Standardvärdet för denna egenskap är 300 dpi. |

### Se även

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
