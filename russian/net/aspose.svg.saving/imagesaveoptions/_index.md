---
title: "Класс ImageSaveOptions"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Saving.ImageSaveOptions. Специфический класс данных параметров"
type: docs
weight: 5690
url: /ru/net/aspose.svg.saving/imagesaveoptions/
---
## ImageSaveOptions class

Класс данных конкретных параметров.

```csharp
public class ImageSaveOptions : ImageRenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Инициализирует новый экземпляр класса `ImageSaveOptions`; в качестве формата изображения по умолчанию будет использоваться Png. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(*[ImageFormat](../../aspose.svg.rendering.image/imageformat/)*) | Формат изображения [`ImageFormat`](../../aspose.svg.rendering.image/imageformat/) на основе инициализации |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | Получает или задает Color, который будет заполнять фон каждой страницы. Значение по умолчанию — Transparent. |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Устанавливает или получает Tagged Image File Format (TIFF) [`Compression`](../../aspose.svg.rendering.image/compression/). По умолчанию это свойство равно LZW. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | Получает объект [`CssOptions`](../../aspose.svg.rendering/cssoptions/), используемый для настройки обработки свойств CSS. |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | Устанавливает или получает [`ImageFormat`](../../aspose.svg.rendering.image/imageformat/). По умолчанию это свойство равно Png. |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Устанавливает или получает горизонтальное разрешение для выходных и внутренних (используемых при обработке фильтров) изображений в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | Получает объект настройки страницы, используемый для конфигурации выходного набора страниц. |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | Получает объект [`TextOptions`](../../aspose.svg.rendering.image/textoptions/), который используется для настройки рендеринга текста. |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | Указывает, использовать ли сглаживание. По умолчанию сглаживание включено. |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Устанавливает или получает вертикальное разрешение для выходных и внутренних (используемых при обработке фильтров) изображений в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |

### См. также

* class [ImageRenderingOptions](../../aspose.svg.rendering.image/imagerenderingoptions/)
* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
