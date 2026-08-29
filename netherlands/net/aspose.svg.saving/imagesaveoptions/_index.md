---
title: "ImageSaveOptions Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Saving.ImageSaveOptions klasse. Specifieke opties gegevensklasse"
type: docs
weight: 5690
url: /nl/net/aspose.svg.saving/imagesaveoptions/
---
## ImageSaveOptions class

Specifieke opties dataklasse.

```csharp
public class ImageSaveOptions : ImageRenderingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Initialiseert een nieuwe instantie van de `ImageSaveOptions` klasse; Png wordt gebruikt als standaard afbeeldingsformaat. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(*[ImageFormat](../../aspose.svg.rendering.image/imageformat/)*) | Afbeeldingsformaat [`ImageFormat`](../../aspose.svg.rendering.image/imageformat/) gebaseerd op initialisatie |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | Haalt op of stelt Color in die de achtergrond van elke pagina zal vullen. Standaardwaarde is Transparant. |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Stelt in of haalt Tagged Image File Format (TIFF) [`Compression`](../../aspose.svg.rendering.image/compression/) op. Standaard is deze eigenschap LZW. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | Haalt een [`CssOptions`](../../aspose.svg.rendering/cssoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van CSS-eigenschappen. |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | Stelt in of haalt [`ImageFormat`](../../aspose.svg.rendering.image/imageformat/) op. Standaard is deze eigenschap Png. |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Stelt in of haalt horizontale resolutie voor uitvoer‑ en interne (die worden gebruikt tijdens filterverwerking) afbeeldingen op, in pixels per inch. Standaard is deze eigenschap 300 dpi. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | Haalt een paginainstellingsobject op dat wordt gebruikt voor de configuratie van de output-pagina-instelling. |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | Haalt een [`TextOptions`](../../aspose.svg.rendering.image/textoptions/) object op dat wordt gebruikt voor de configuratie van tekstweergave. |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | Specificeert of anti‑aliasing moet worden gebruikt. Standaard is anti‑aliasing ingeschakeld. |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Stelt in of haalt verticale resolutie voor uitvoer‑ en interne (die worden gebruikt tijdens filterverwerking) afbeeldingen op, in pixels per inch. Standaard is deze eigenschap 300 dpi. |

### Zie ook

* class [ImageRenderingOptions](../../aspose.svg.rendering.image/imagerenderingoptions/)
* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
