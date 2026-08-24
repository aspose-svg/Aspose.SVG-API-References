---
title: "ImageRenderingOptions 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Image.ImageRenderingOptions 类。表示 ImageDevice 的渲染选项。此选项用于指定输出图像格式、压缩、分辨率等。"
type: docs
weight: 4940
url: /zh/net/aspose.svg.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

表示 [`ImageDevice`](../imagedevice/) 的渲染选项。此选项用于指定输出图像格式、压缩、分辨率等。

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | 初始化 `ImageRenderingOptions` 类的新实例；默认使用 Png 作为图像格式。 |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | 使用指定的图像格式初始化 `ImageRenderingOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | 获取或设置用于填充每页背景的颜色。默认值为 Transparent。 |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | 设置或获取标记图像文件格式（TIFF）[`Compression`](../compression/)。默认此属性为 LZW。 |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../aspose.svg.rendering/cssoptions/) 对象。 |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | 设置或获取 [`ImageFormat`](../imageformat/)。默认此属性为 Png。 |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 设置或获取输出和内部（用于过滤器处理期间）图像的水平分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | 获取用于配置输出页面设置的页面设置对象。 |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | 获取一个用于配置文本渲染的 [`TextOptions`](../textoptions/) 对象。 |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | 指定是否使用抗锯齿。默认情况下，已启用抗锯齿。 |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 设置或获取输出和内部（用于过滤器处理期间）图像的垂直分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |

### 另请参阅

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
