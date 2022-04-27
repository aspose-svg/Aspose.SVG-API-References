---
title: CSSPrimitiveValue
second_title: Aspose.SVG for .NET API Reference
description: 
type: docs
weight: 480
url: /net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

The CSSPrimitiveValue interface represents a single CSS value. This interface may be used to determine the value of a specific style property currently set in a block or to set a specific style property explicitly within the block. An instance of this interface might be obtained from the getPropertyCSSValue method of the CSSStyleDeclaration interface. A CSSPrimitiveValue object only occurs in a context of a CSS property.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Properties

| Name | Description |
| --- | --- |
| [PrimitiveType](primitivetype) { get; } | The type of the value as defined by the constants specified above. |

## Methods

| Name | Description |
| --- | --- |
| abstract [GetCounterValue](getcountervalue)() | This method is used to get the Counter value. If this CSS value doesn't contain a counter value, a DOMException is raised. Modification to the corresponding style property can be achieved using the Counter interface. |
| abstract [GetFloatValue](getfloatvalue)(ushort) | This method is used to get a float value in a specified unit. If this CSS value doesn't contain a float value or can't be converted into the specified unit, a DOMException is raised. |
| abstract [GetIntValue](getintvalue)(ushort) | This method is used to get an int value in a specified unit. If this CSS value doesn't contain an int value or can't be converted into the specified unit, a DOMException is raised. |
| abstract [GetRectValue](getrectvalue)() | This method is used to get the Rect value. If this CSS value doesn't contain a rect value, a DOMException is raised. Modification to the corresponding style property can be achieved using the Rect interface. |
| abstract [GetRGBColorValue](getrgbcolorvalue)() | This method is used to get the RGB color. If this CSS value doesn't contain a RGB color value, a DOMException is raised. Modification to the corresponding style property can be achieved using the RGBColor interface. |
| abstract [GetStringValue](getstringvalue)() | This method is used to get the string value. If the CSS value doesn't contain a string value, a DOMException is raised. |
| abstract [SetFloatValue](setfloatvalue)(ushort, float) | A method to set the float value with a specified unit. If the property attached with this value can not accept the specified unit or the float value, the value will be unchanged and a DOMException will be raised. |
| abstract [SetIntValue](setintvalue)(ushort, int) | A method to set the int value with a specified unit. If the property attached with this value can not accept the specified unit or the int value, the value will be unchanged and a DOMException will be raised. |
| abstract [SetStringValue](setstringvalue)(ushort, string) | A method to set the string value with the specified unit. If the property attached to this value can't accept the specified unit or the string value, the value will be unchanged and a DOMException will be raised. |

## Other Members

| Name | Description |
| --- | --- |
| const [CSS_ATTR](css_attr) | The value is a attribute function. The value can be obtained by using the getStringValue method. |
| const [CSS_CH](css_ch) | The value is a length (ch). The value can be obtained by using the getFloatValue method. |
| const [CSS_CM](css_cm) | The value is a length (cm). The value can be obtained by using the getFloatValue method. |
| const [CSS_COUNTER](css_counter) | The value is a counter or counters function. The value can be obtained by using the GetCounterValue method. |
| const [CSS_DEG](css_deg) | The value is an angle (deg). The value can be obtained by using the getFloatValue method. |
| const [CSS_DIMENSION](css_dimension) | The value is a number with an unknown dimension. The value can be obtained by using the getFloatValue method. |
| const [CSS_DPCM](css_dpcm) | The value is a dots per centimeter (dpcm). |
| const [CSS_DPI](css_dpi) | The value is a dots per inch (dpi). |
| const [CSS_DPPX](css_dppx) | The value is a dots per ‘px’ unit (dppx). |
| const [CSS_EMS](css_ems) | The value is a length (ems). The value can be obtained by using the getFloatValue method. |
| const [CSS_EXS](css_exs) | The value is a length (exs). The value can be obtained by using the getFloatValue method. |
| const [CSS_GRAD](css_grad) | The value is an angle (grad). The value can be obtained by using the getFloatValue method. |
| const [CSS_HZ](css_hz) | The value is a frequency (Hz). The value can be obtained by using the getFloatValue method. |
| const [CSS_IDENT](css_ident) | The value is an identifier. The value can be obtained by using the getStringValue method. |
| const [CSS_IN](css_in) | The value is a length (in). The value can be obtained by using the getFloatValue method. |
| const [CSS_KHZ](css_khz) | The value is a frequency (kHz). The value can be obtained by using the getFloatValue method. |
| const [CSS_MM](css_mm) | The value is a length (mm). The value can be obtained by using the getFloatValue method. |
| const [CSS_MS](css_ms) | The value is a time (ms). The value can be obtained by using the getFloatValue method. |
| const [CSS_NUMBER](css_number) | The value is a simple number. The value can be obtained by using the getFloatValue method. |
| const [CSS_PC](css_pc) | The value is a length (pc). The value can be obtained by using the getFloatValue method. |
| const [CSS_PERCENTAGE](css_percentage) | The value is a percentage. The value can be obtained by using the getFloatValue method. |
| const [CSS_PT](css_pt) | The value is a length (pt). The value can be obtained by using the getFloatValue method. |
| const [CSS_PX](css_px) | The value is a length (px). The value can be obtained by using the getFloatValue method. |
| const [CSS_RAD](css_rad) | The value is an angle (rad). The value can be obtained by using the getFloatValue method. |
| const [CSS_RECT](css_rect) | The value is a rect function. The value can be obtained by using the GetRectValue method. |
| const [CSS_REM](css_rem) | The value is a length (rem). The value can be obtained by using the getFloatValue method. |
| const [CSS_RGBCOLOR](css_rgbcolor) | The value is a RGB color. The value can be obtained by using the GetRGBColorValue method. |
| const [CSS_S](css_s) | The value is a time (s). The value can be obtained by using the getFloatValue method. |
| const [CSS_STRING](css_string) | The value is a STRING. The value can be obtained by using the getStringValue method. |
| const [CSS_UNKNOWN](css_unknown) | The value is not a recognized CSS2 value. The value can only be obtained by using the cssText attribute. |
| const [CSS_URI](css_uri) | The value is a URI. The value can be obtained by using the getStringValue method. |
| const [CSS_VH](css_vh) | The value is a percentage of the full viewport height. |
| const [CSS_VMAX](css_vmax) | The value is a percentage of the viewport width or height, whichever is larger. |
| const [CSS_VMIN](css_vmin) | The value is a percentage of the viewport width or height, whichever is smaller. |
| const [CSS_VW](css_vw) | The value is a percentage of the full viewport width. |

### See Also

* class [CSSValue](../cssvalue)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css)
* assembly [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
