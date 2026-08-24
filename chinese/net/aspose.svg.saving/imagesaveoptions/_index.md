---
title: "ImageSaveOptions 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Saving.ImageSaveOptions 类。特定选项数据类"
type: docs
weight: 5690
url: /zh/net/aspose.svg.saving/imagesaveoptions/
---
## ImageSaveOptions class

特定选项数据类。

```csharp
public class ImageSaveOptions : ImageRenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | 初始化 `ImageSaveOptions` 类的新实例；默认图像格式将使用 Png。 |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(*[ImageFormat](../../aspose.svg.rendering.image/imageformat/)*) | 基于初始化的图像格式[`ImageFormat`](../../aspose.svg.rendering.image/imageformat/)。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | 获取或设置用于填充每页背景的颜色。默认值为 Transparent。 |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | 设置或获取 Tagged Image File Format（TIFF）[`Compression`](../../aspose.svg.rendering.image/compression/)。默认此属性为 LZW。 |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../aspose.svg.rendering/cssoptions/) 对象。 |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | 设置或获取[`ImageFormat`](../../aspose.svg.rendering.image/imageformat/)。默认此属性为 Png。 |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 设置或获取输出和内部（用于过滤器处理期间）图像的水平分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | 获取用于配置输出页面设置的页面设置对象。 |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | 获取一个用于文本渲染配置的[`TextOptions`](../../aspose.svg.rendering.image/textoptions/)对象。 |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | 指定是否使用抗锯齿。默认情况下，已启用抗锯齿。 |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 设置或获取输出和内部（用于过滤器处理期间）图像的垂直分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |

### 另请参阅

* class [ImageRenderingOptions](../../aspose.svg.rendering.image/imagerenderingoptions/)
* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
