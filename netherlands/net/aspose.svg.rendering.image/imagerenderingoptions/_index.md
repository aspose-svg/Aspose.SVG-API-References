---
title: "ImageRenderingOptions‑klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Rendering.Image.ImageRenderingOptions‑klasse. Stelt render‑opties voor ImageDevice voor. Deze optie wordt gebruikt om het uitvoer‑afbeeldingsformaat, compressie, resolutie enz. op te geven."
type: docs
weight: 4940
url: /nl/net/aspose.svg.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Stelt render‑opties voor [`ImageDevice`](../imagedevice/) voor. Deze optie wordt gebruikt om het uitvoer‑afbeeldingsformaat, compressie, resolutie enz. op te geven.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initialiseert een nieuw exemplaar van de `ImageRenderingOptions`‑klasse; Png wordt gebruikt als standaard‑afbeeldingsformaat. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | Initialiseert een nieuw exemplaar van de `ImageRenderingOptions`‑klasse met het opgegeven afbeeldingsformaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | Haalt op of stelt Color in die de achtergrond van elke pagina zal vullen. Standaardwaarde is Transparant. |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Stelt in of haalt Tagged Image File Format (TIFF) [`Compression`](../compression/) op. Standaard is deze eigenschap LZW. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | Haalt een [`CssOptions`](../../aspose.svg.rendering/cssoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van CSS-eigenschappen. |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | Stelt in of haalt [`ImageFormat`](../imageformat/) op. Standaard is deze eigenschap Png. |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Stelt in of haalt horizontale resolutie voor uitvoer‑ en interne (die worden gebruikt tijdens filterverwerking) afbeeldingen op, in pixels per inch. Standaard is deze eigenschap 300 dpi. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | Haalt een paginainstellingsobject op dat wordt gebruikt voor de configuratie van de output-pagina-instelling. |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | Haalt een [`TextOptions`](../textoptions/)‑object op dat wordt gebruikt voor de configuratie van tekstweergave. |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | Specificeert of anti‑aliasing moet worden gebruikt. Standaard is anti‑aliasing ingeschakeld. |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Stelt in of haalt verticale resolutie voor uitvoer‑ en interne (die worden gebruikt tijdens filterverwerking) afbeeldingen op, in pixels per inch. Standaard is deze eigenschap 300 dpi. |

### Zie ook

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
