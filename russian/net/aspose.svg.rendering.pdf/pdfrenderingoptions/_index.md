---
title: "Класс PdfRenderingOptions"
second_title: "Aspose.SVG для .NET справочник API"
description: "**Aspose.Svg.Rendering.Pdf.PdfRenderingOptions** класс. Представляет параметры рендеринга для PdfDevice."
type: docs
weight: 5050
url: /ru/net/aspose.svg.rendering.pdf/pdfrenderingoptions/
---
## PdfRenderingOptions class

Представляет параметры рендеринга для [`PdfDevice`](../pdfdevice/).

```csharp
public class PdfRenderingOptions : RenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfRenderingOptions](pdfrenderingoptions/)() | Инициализирует новый экземпляр класса `PdfRenderingOptions`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | Получает или задает Color, который будет заполнять фон каждой страницы. Значение по умолчанию — Transparent. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | Получает объект [`CssOptions`](../../aspose.svg.rendering/cssoptions/), используемый для настройки обработки свойств CSS. |
| [DocumentInfo](../../aspose.svg.rendering.pdf/pdfrenderingoptions/documentinfo/) { get; } | Содержит информацию о выходном PDF‑документе. |
| [Encryption](../../aspose.svg.rendering.pdf/pdfrenderingoptions/encryption/) { get; set; } | Получает или задает детали шифрования. Если не задано, шифрование не будет выполнено. |
| [FormFieldBehaviour](../../aspose.svg.rendering.pdf/pdfrenderingoptions/formfieldbehaviour/) { get; set; } | Указывает поведение полей формы в выходном PDF‑документе. |
| virtual [HorizontalResolution](../../aspose.svg.rendering/renderingoptions/horizontalresolution/) { get; set; } | Устанавливает или получает горизонтальное разрешение внутренних (используемых при обработке фильтров) изображений в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
| [IsTaggedPdf](../../aspose.svg.rendering.pdf/pdfrenderingoptions/istaggedpdf/) { get; set; } | Создаёт структуру тегов, если `true`. |
| [JpegQuality](../../aspose.svg.rendering.pdf/pdfrenderingoptions/jpegquality/) { get; set; } | Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). По умолчанию 95. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | Получает объект настройки страницы, используемый для конфигурации выходного набора страниц. |
| virtual [VerticalResolution](../../aspose.svg.rendering/renderingoptions/verticalresolution/) { get; set; } | Устанавливает или получает вертикальное разрешение внутренних (используемых при обработке фильтров) изображений в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |

### См. также

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Pdf](../../aspose.svg.rendering.pdf/)
* assembly [Aspose.SVG](../../)
