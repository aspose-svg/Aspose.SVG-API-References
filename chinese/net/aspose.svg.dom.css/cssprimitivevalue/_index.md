---
title: "CSSPrimitiveValue 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.CSSPrimitiveValue 类。CSSPrimitiveValue 接口表示单个 CSS 值。该接口可用于确定块中当前设置的特定样式属性的值，或在块内显式设置特定样式属性。可以通过 CSSStyleDeclaration 接口的 getPropertyCSSValue 方法获取该接口的实例。CSSPrimitiveValue 对象仅出现在 CSS 属性的上下文中。"
type: docs
weight: 2480
url: /zh/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue 接口表示单个 CSS 值。该接口可用于确定块中当前设置的特定样式属性的值，或在块内显式设置特定样式属性。可以通过 CSSStyleDeclaration 接口的 getPropertyCSSValue 方法获取该接口的实例。CSSPrimitiveValue 对象仅在 CSS 属性的上下文中出现。

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) 接口的 CSSText 属性表示当前计算的 CSS 属性值。 |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | 定义该值类型的代码。 |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | 值的类型，由上述常量定义。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | 确定指定的 Object 是否等于此实例。 |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | 此方法用于获取 Counter 值。如果此 CSS 值不包含计数器值，则会抛出 DOMException。可以使用 Counter 接口对相应的样式属性进行修改。 |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(*ushort*) | 此方法用于获取指定单位的浮点值。如果此 CSS 值不包含浮点值或无法转换为指定单位，则会抛出 DOMException。 |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(*ushort*) | 此方法用于获取指定单位的整数值。如果此 CSS 值不包含整数值或无法转换为指定单位，则会抛出 DOMException。 |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | 此方法用于获取 Rect 值。如果此 CSS 值不包含 rect 值，则会抛出 DOMException。可以使用 Rect 接口对相应的样式属性进行修改。 |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | 此方法用于获取 RGB 颜色。如果此 CSS 值不包含 RGB 颜色值，则会抛出 DOMException。可以使用 RGBColor 接口对相应的样式属性进行修改。 |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | 此方法用于获取字符串值。如果 CSS 值不包含字符串值，则会抛出 DOMException。 |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(*ushort, float*) | 一种使用指定单位设置浮点值的方法。如果附加此值的属性不能接受指定单位或浮点值，则该值保持不变，并抛出 DOMException。 |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(*ushort, int*) | 一种使用指定单位设置整数值的方法。如果附加此值的属性不能接受指定单位或整数值，则该值保持不变，并抛出 DOMException。 |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(*ushort, string*) | 一种使用指定单位设置字符串值的方法。如果附加此值的属性不能接受指定单位或字符串值，则该值保持不变，并抛出 DOMException。 |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | 返回表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | 该值是属性函数。可以使用 getStringValue 方法获取该值。 |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | 该值是长度 (ch)。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | 该值是长度 (cm)。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | 该值是 counter 或 counters 函数。可以使用 GetCounterValue 方法获取该值。 |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | 该值是角度 (deg)。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | 该值是具有未知维度的数值。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | 该值是每厘米点数 (dpcm)。 |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | 该值是每英寸点数 (dpi)。 |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | 该值是每 ‘px’ 单位的点数 (dppx)。 |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | 该值是长度（ems）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | 该值是长度（exs）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_FR](../../aspose.svg.dom.css/cssprimitivevalue/css_fr/) | 弹性长度或 flex 是一种使用 fr 单位的尺寸，表示网格容器中剩余空间的一个分数。 |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | 该值是角度（grad）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | 该值是频率（Hz）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | 该值是标识符。该值可通过使用 getStringValue 方法获取。 |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | 该值是长度（in）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | 该值是频率（kHz）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | 该值是长度（mm）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | 该值是时间（ms）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | 该值是普通数字。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | 该值是长度（pc）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | 该值是百分比。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | 该值是长度（pt）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | 该值是长度（px）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | 该值是角度（rad）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | 该值是 rect 函数。该值可通过使用 GetRectValue 方法获取。 |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | 该值是长度（rem）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | 该值是 RGB 颜色。该值可通过使用 GetRGBColorValue 方法获取。 |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | 该值是时间（s）。该值可通过使用 getFloatValue 方法获取。 |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | 该值是字符串（STRING）。该值可通过使用 getStringValue 方法获取。 |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | 该值不是已识别的 CSS2 值。该值只能通过使用 cssText 属性获取。 |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | 该值是 URI。该值可通过使用 getStringValue 方法获取。 |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | 该值是完整视口高度的百分比。 |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | 该值是视口宽度或高度的百分比，以较大者为准。 |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | 该值是视口宽度或高度的百分比，以较小者为准。 |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | 该值是完整视口宽度的百分比。 |
| const [CSS_X](../../aspose.svg.dom.css/cssprimitivevalue/css_x/) | 该值是每‘px’单位的点数 (x)。 |

### 另请参阅

* class [CSSValue](../cssvalue/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
