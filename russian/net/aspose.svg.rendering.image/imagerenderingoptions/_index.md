---
title: "Класс ImageRenderingOptions"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Rendering.Image.ImageRenderingOptions. Представляет параметры отрисовки для ImageDevice. Эти параметры используются для указания формата выходного изображения, сжатия, разрешения и т.д."
type: docs
weight: 4940
url: /ru/net/aspose.svg.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Представляет параметры отрисовки для [`ImageDevice`](../imagedevice/). Эти параметры используются для указания формата выходного изображения, сжатия, разрешения и т.д.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Инициализирует новый экземпляр класса `ImageRenderingOptions`; в качестве формата изображения по умолчанию будет использоваться PNG. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | Инициализирует новый экземпляр класса `ImageRenderingOptions` с указанным форматом изображения. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | Получает или задает Color, который будет заполнять фон каждой страницы. Значение по умолчанию — Transparent. |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Устанавливает или получает параметр сжатия Tagged Image File Format (TIFF) [`Compression`](../compression/). По умолчанию это свойство имеет значение LZW. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | Получает объект [`CssOptions`](../../aspose.svg.rendering/cssoptions/), используемый для настройки обработки свойств CSS. |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | Устанавливает или получает [`ImageFormat`](../imageformat/). По умолчанию это свойство имеет значение PNG. |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Устанавливает или получает горизонтальное разрешение для выходных и внутренних (используемых при обработке фильтров) изображений в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | Получает объект настройки страницы, используемый для конфигурации выходного набора страниц. |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | Получает объект [`TextOptions`](../textoptions/), который используется для настройки отрисовки текста. |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | Указывает, использовать ли сглаживание. По умолчанию сглаживание включено. |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Устанавливает или получает вертикальное разрешение для выходных и внутренних (используемых при обработке фильтров) изображений в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |

### См. также

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
