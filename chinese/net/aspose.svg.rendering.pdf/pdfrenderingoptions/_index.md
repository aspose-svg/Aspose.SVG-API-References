---
title: "PdfRenderingOptions 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Pdf.PdfRenderingOptions 类。表示用于 PdfDevice 的渲染选项。"
type: docs
weight: 5050
url: /zh/net/aspose.svg.rendering.pdf/pdfrenderingoptions/
---
## PdfRenderingOptions class

表示用于 [`PdfDevice`](../pdfdevice/) 的渲染选项。

```csharp
public class PdfRenderingOptions : RenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfRenderingOptions](pdfrenderingoptions/)() | 初始化 `PdfRenderingOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | 获取或设置用于填充每页背景的颜色。默认值为 Transparent。 |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../aspose.svg.rendering/cssoptions/) 对象。 |
| [DocumentInfo](../../aspose.svg.rendering.pdf/pdfrenderingoptions/documentinfo/) { get; } | 包含有关输出 PDF 文档的信息。 |
| [Encryption](../../aspose.svg.rendering.pdf/pdfrenderingoptions/encryption/) { get; set; } | 获取或设置加密细节。如果未设置，则不会执行加密。 |
| [FormFieldBehaviour](../../aspose.svg.rendering.pdf/pdfrenderingoptions/formfieldbehaviour/) { get; set; } | 指定输出 PDF 文档中表单字段的行为。 |
| virtual [HorizontalResolution](../../aspose.svg.rendering/renderingoptions/horizontalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的水平分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |
| [IsTaggedPdf](../../aspose.svg.rendering.pdf/pdfrenderingoptions/istaggedpdf/) { get; set; } | 如果为 `true`，则创建标签结构。 |
| [JpegQuality](../../aspose.svg.rendering.pdf/pdfrenderingoptions/jpegquality/) { get; set; } | 指定图像的 JPEG 压缩质量（如果使用 JPEG 压缩）。默认值为 95。 |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | 获取用于配置输出页面设置的页面设置对象。 |
| virtual [VerticalResolution](../../aspose.svg.rendering/renderingoptions/verticalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的垂直分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |

### 另请参阅

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Pdf](../../aspose.svg.rendering.pdf/)
* assembly [Aspose.SVG](../../)
