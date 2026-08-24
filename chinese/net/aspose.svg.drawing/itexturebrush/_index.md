---
title: "ITextureBrush 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Drawing.ITextureBrush 接口。定义使用图像填充形状内部的画笔接口。"
type: docs
weight: 3520
url: /zh/net/aspose.svg.drawing/itexturebrush/
---
## ITextureBrush interface

定义使用图像填充形状内部的画笔接口。

```csharp
public interface ITextureBrush : ITransformableBrush
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ColorMap](../../aspose.svg.drawing/itexturebrush/colormap/) { get; } | 元素数量必须为偶数。每个偶数索引的元素是旧颜色。每个奇数索引的元素是新颜色。 |
| [Image](../../aspose.svg.drawing/itexturebrush/image/) { get; } | 获取或设置画笔使用的图像。 |
| [ImageArea](../../aspose.svg.drawing/itexturebrush/imagearea/) { get; } | 指定画笔使用的图像的部分。如果等于 RectangleF.Empty，则使用整幅图像。坐标以像素为单位。 |
| [Opacity](../../aspose.svg.drawing/itexturebrush/opacity/) { get; set; } | 获取颜色变换矩阵中的不透明度值。 |

### 另请参阅

* interface [ITransformableBrush](../itransformablebrush/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
