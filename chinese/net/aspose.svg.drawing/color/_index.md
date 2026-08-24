---
title: "Color 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Drawing.Color 类。Color 类允许您使用红绿蓝 RGB 值、色相-饱和度-亮度 HSL 值、色相-饱和度-数值 HSV 值、色相-白度-黑度 HWB 值、亮度-A-B LAB 值、亮度-色度-色相 LCH 值、青品黄-关键色 CMYK 值、自然颜色 NCOL 值，或使用颜色名称来指定颜色。还提供 Alpha 通道以指示透明度。"
type: docs
weight: 3390
url: /zh/net/aspose.svg.drawing/color/
---
## Color class

Color 类允许您以红绿蓝 (RGB) 值、色相-饱和度-亮度 (HSL) 值、色相-饱和度-数值 (HSV) 值、色相-白度-黑度 (HWB) 值、亮度-A-B (LAB) 值、亮度-色度-色相 (LCH) 值、青品红-品黄-键 (CMYK) 值、自然色 (NCOL) 值，或使用颜色名称来指定颜色。还提供 Alpha 通道以指示透明度。

```csharp
public class Color
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Color](color/#constructor)() | 初始化 `Color` 类的新实例。默认颜色为黑色。 |
| [Color](color/#constructor_1)(*byte, byte, byte*) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-255 范围内。 |
| [Color](color/#constructor_5)(*float, float, float*) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-1 范围内。 |
| [Color](color/#constructor_3)(*int, int, int*) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-255 范围内。 |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-255 范围内。 |
| [Color](color/#constructor_6)(*float, float, float, float*) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-1 范围内。 |
| [Color](color/#constructor_4)(*int, int, int, int*) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-255 范围内。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alpha](../../aspose.svg.drawing/color/alpha/) { get; } | 表示颜色的 alpha 分量。 |
| [Blue](../../aspose.svg.drawing/color/blue/) { get; } | 表示颜色的蓝色分量。 |
| [Green](../../aspose.svg.drawing/color/green/) { get; } | 表示颜色的绿色分量。 |
| [Red](../../aspose.svg.drawing/color/red/) { get; } | 表示颜色的红色分量 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromCmyk](../../aspose.svg.drawing/color/fromcmyk/)(*float, float, float, float*) | 返回一个具有请求的青色、品红、黄色、关键（黑色）值的新 Color。 |
| static [FromCmyka](../../aspose.svg.drawing/color/fromcmyka/)(*float, float, float, float, float*) | 返回一个具有请求的青色、品红、黄色、关键（黑色）和 alpha 值的新 Color。 |
| static [FromGray](../../aspose.svg.drawing/color/fromgray/)(*float*) | 返回一个具有请求的灰度值的新 Color。 |
| static [FromHsl](../../aspose.svg.drawing/color/fromhsl/)(*float, float, float*) | 返回一个具有请求的色相、饱和度、饱和度值的新 Color。 |
| static [FromHsla](../../aspose.svg.drawing/color/fromhsla/)(*float, float, float, float*) | 返回一个具有请求的色相、饱和度、饱和度和 alpha 值的新 Color。 |
| static [FromHsv](../../aspose.svg.drawing/color/fromhsv/)(*float, float, float*) | 返回一个具有请求的色相、饱和度、数值的新 Color。 |
| static [FromHsva](../../aspose.svg.drawing/color/fromhsva/)(*float, float, float, float*) | 返回一个具有请求的色相、饱和度、数值和 alpha 的新 Color。 |
| static [FromHwb](../../aspose.svg.drawing/color/fromhwb/)(*float, float, float*) | 返回一个具有请求的色相、亮度、暗度值的新 Color。 |
| static [FromHwba](../../aspose.svg.drawing/color/fromhwba/)(*float, float, float, float*) | 返回一个具有请求的色相、亮度、暗度值的新 Color。 |
| static [FromInt](../../aspose.svg.drawing/color/fromint/)(*int*) | 返回一个具有请求的 ARGB 值的新 Color。 |
| static [FromLab](../../aspose.svg.drawing/color/fromlab/)(*float, float, float*) | 返回一个具有请求的亮度、A、B 值的新 Color。 |
| static [FromLaba](../../aspose.svg.drawing/color/fromlaba/)(*float, float, float, float*) | 返回一个具有请求的亮度、A、B 和 alpha 值的新 Color。 |
| static [FromLch](../../aspose.svg.drawing/color/fromlch/)(*float, float, float*) | 返回一个具有请求的亮度、色度、色相值的新 Color。 |
| static [FromLcha](../../aspose.svg.drawing/color/fromlcha/)(*float, float, float, float*) | 返回一个具有请求的亮度、色度、色相和 alpha 值的新 Color。 |
| static [FromOklab](../../aspose.svg.drawing/color/fromoklab/)(*float, float, float*) | 返回一个针对 OKLAB 模型、具有请求的亮度、A、B 值的新 Color。 |
| static [FromOklaba](../../aspose.svg.drawing/color/fromoklaba/)(*float, float, float, float*) | 返回一个针对 OKLAB 模型、具有请求的亮度、A、B 和 alpha 值的新 Color。 |
| static [FromOklch](../../aspose.svg.drawing/color/fromoklch/)(*float, float, float*) | 返回一个针对 OKLAB 模型、具有请求的亮度、色度、色相值的新 Color。 |
| static [FromOklcha](../../aspose.svg.drawing/color/fromoklcha/)(*float, float, float, float*) | 返回一个针对 OKLAB 模型、具有请求的亮度、色度、色相和 alpha 值的新 Color。 |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | 返回一个具有请求的 ged、绿色、蓝色值的新 Color。所有颜色分量必须在 0-255 范围内。 |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | 返回一个具有请求的 ged、绿色、蓝色值的新 Color。所有颜色分量必须在 0-1 范围内。 |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | 返回一个具有请求的 ged、绿色、蓝色值的新 Color。所有颜色分量必须在 0-255 范围内。 |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | 返回一个具有请求的 ged、绿色、蓝色和 alpha 值的新 Color。所有颜色分量必须在 0-255 范围内。 |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | 返回一个具有请求的 ged、绿色、蓝色和 alpha 值的新 Color。所有颜色分量必须在 0-1 范围内。 |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | 返回一个具有请求的 ged、绿色、蓝色和 alpha 值的新 Color。所有颜色分量必须在 0-255 范围内。 |
| static [FromString](../../aspose.svg.drawing/color/fromstring/)(*string*) | 解析包含 CSS 颜色的字符串并返回一个新 Color。 |
| static [FromUint](../../aspose.svg.drawing/color/fromuint/)(*uint*) | 返回一个具有请求的 ARGB 值的新 Color。 |
| [AddLuminosity](../../aspose.svg.drawing/color/addluminosity/)(*float*) | 创建一个 Color 的副本，其亮度与 delta 值的和。 |
| [Convert](../../aspose.svg.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | 以指定颜色模型的格式返回颜色分量。 |
| override [Equals](../../aspose.svg.drawing/color/equals/)(*object*) | 确定指定的 `Color` 是否等于此实例。 |
| [GetComplementary](../../aspose.svg.drawing/color/getcomplementary/)() | 返回一个新颜色，该颜色位于原始颜色的色轮相对侧。 |
| override [GetHashCode](../../aspose.svg.drawing/color/gethashcode/)() | 返回哈希码。 |
| [GetHue](../../aspose.svg.drawing/color/gethue/)() | 返回该 Color 的色相。 |
| [GetLuminosity](../../aspose.svg.drawing/color/getluminosity/)() | 返回该 Color 的亮度。 |
| [GetSaturation](../../aspose.svg.drawing/color/getsaturation/)() | 返回该 Color 的饱和度。 |
| [ToInt](../../aspose.svg.drawing/color/toint/)() | 将 Color 的 ARGB 组件编码为 int。 |
| [ToName](../../aspose.svg.drawing/color/toname/)() | 如果颜色匹配 CSS 命名颜色列表中的颜色，则返回该颜色的名称；否则返回空字符串。 |
| [ToNaturalColorString](../../aspose.svg.drawing/color/tonaturalcolorstring/)(*int*) | 返回使用颜色字母和数字指定距离（百分比）的自然颜色 (NCol)。 |
| [ToRgbaHexString](../../aspose.svg.drawing/color/torgbahexstring/)() | 返回使用十六进制表示的颜色，格式为：#RRGGBBAA。 |
| [ToRgbaString](../../aspose.svg.drawing/color/torgbastring/)() | 返回包含 RGBA 颜色的字符串，格式为：rgba(R, G, B, A)。 |
| [ToRgbHexString](../../aspose.svg.drawing/color/torgbhexstring/)() | 返回使用十六进制表示的颜色，格式为：#RRGGBB。 |
| [ToRgbString](../../aspose.svg.drawing/color/torgbstring/)() | 返回包含 RGB 颜色的字符串，格式为：rgb(R, G, B)。 |
| override [ToString](../../aspose.svg.drawing/color/tostring/)() | 返回由 RGBA 组件值组成的字符串。 |
| [ToUint](../../aspose.svg.drawing/color/touint/)() | 将 Color 的 ARGB 组件编码为无符号 int。 |
| [WithAlpha](../../aspose.svg.drawing/color/withalpha/)(*float*) | 创建具有指定 alpha 组件的 Color 副本。 |
| [WithHue](../../aspose.svg.drawing/color/withhue/)(*float*) | 创建具有指定色相的 Color 副本。 |
| [WithLuminosity](../../aspose.svg.drawing/color/withluminosity/)(*float*) | 创建具有指定亮度的 Color 副本。 |
| [WithSaturation](../../aspose.svg.drawing/color/withsaturation/)(*float*) | 创建具有指定饱和度的 Color 副本。 |

### 另请参阅

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
