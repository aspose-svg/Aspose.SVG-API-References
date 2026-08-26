---
title: "ImageRenderingOptions Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Rendering.Image.ImageRenderingOptions Klasse. Stellt Renderoptionen für ImageDevice dar. Diese Optionen werden verwendet, um Ausgabe‑Bildformat, Kompression, Auflösung usw. anzugeben."
type: docs
weight: 4940
url: /de/net/aspose.svg.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Stellt Renderoptionen für [`ImageDevice`](../imagedevice/) dar. Diese Optionen werden verwendet, um Ausgabe‑Bildformat, Kompression, Auflösung usw. anzugeben.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initialisiert eine neue Instanz der `ImageRenderingOptions` Klasse; Png wird als Standard‑Bildformat verwendet. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | Initialisiert eine neue Instanz der `ImageRenderingOptions` Klasse mit dem angegebenen Bildformat. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | Liest oder setzt die Farbe, die den Hintergrund jeder Seite füllt. Der Standardwert ist Transparent. |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Legt fest oder ruft das Tagged Image File Format (TIFF) [`Compression`](../compression/) ab. Standardmäßig ist diese Eigenschaft LZW. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | Liest ein [`CssOptions`](../../aspose.svg.rendering/cssoptions/) Objekt, das für die Konfiguration der Verarbeitung von CSS-Eigenschaften verwendet wird. |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | Legt fest oder ruft [`ImageFormat`](../imageformat/) ab. Standardmäßig ist diese Eigenschaft Png. |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Setzt oder liest die horizontale Auflösung für Ausgabe‑ und interne (die bei der Filterverarbeitung verwendet werden) Bilder in Pixel pro Zoll. Standardmäßig ist diese Eigenschaft 300 dpi. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | Liest ein Seiten-Setup-Objekt, das für die Konfiguration des Ausgabe-Seitenlayouts verwendet wird. |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | Gibt ein [`TextOptions`](../textoptions/) Objekt zurück, das für die Konfiguration der Textdarstellung verwendet wird. |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | Gibt an, ob Antialiasing verwendet werden soll. Standardmäßig ist Antialiasing aktiviert. |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Setzt oder liest die vertikale Auflösung für Ausgabe‑ und interne (die bei der Filterverarbeitung verwendet werden) Bilder in Pixel pro Zoll. Standardmäßig ist diese Eigenschaft 300 dpi. |

### Siehe auch

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
