---
title: "BlendMode 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.BlendMode 枚举。指定在 SVG 中合并图像或元素时可用的混合模式。"
type: docs
weight: 80
url: /zh/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

指定 SVG 中用于合并图像或元素的混合模式。

```csharp
public enum BlendMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Normal | `0` | 显示源图像原样，不进行任何混合。 |
| Multiply | `1` | 将源图像和背景的颜色相乘。结果是更暗的图像。 |
| Screen | `2` | 使源图像的暗部变亮，亮部保持不变。 |
| Overlay | `3` | 结合 Multiply 和 Screen 混合模式以增强对比度。 |
| Darken | `4` | 根据源图像的颜色使背景变暗。 |
| Lighten | `5` | 根据源图像的颜色使背景变亮。 |
| ColorDodge | `6` | 使背景变亮以反映源图像。 |
| ColorBurn | `7` | 使背景变暗以反映源图像。 |
| HardLight | `8` | 基于源图像的亮度创建硬光效果。 |
| SoftLight | `9` | 基于源图像的亮度创建柔光效果。 |
| Difference | `10` | 突出源图像与背景之间的差异。 |
| Exclusion | `11` | 创建类似 Difference 的效果，但对比度较低。 |
| Hue | `12` | 使用源图像的色相结合背景的亮度和饱和度。 |
| Saturation | `13` | 使用源图像的饱和度结合背景的色相和亮度。 |
| Color | `14` | 使用源图像的色相和饱和度结合背景的亮度。 |
| Luminosity | `15` | 使用源图像的亮度结合背景的色相和饱和度。 |

## 备注

SVG 中的混合模式用于确定两个图层如何相互混合。此枚举提供了多种选项，控制混合图层的颜色如何混合并产生不同的视觉效果。

### 另请参阅

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
