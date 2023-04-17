---
title: Class CSSPrimitiveValue
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Dom.Css.CSSPrimitiveValue klas. Die CSSPrimitiveValueSchnittstelle repräsentiert einen einzelnen CSSWert. Diese Schnittstelle kann verwendet werden um den Wert einer bestimmten Stileigenschaft zu bestimmen die derzeit in einem Block festgelegt ist oder um eine bestimmte Stileigenschaft explizit innerhalb des Blocks festzulegen. Eine Instanz dieser Schnittstelle kann von der getPropertyCSSValueMethode der CSSStyleDeclarationSchnittstelle abgerufen werden. Ein CSSPrimitiveValueObjekt kommt nur im Kontext einer CSSEigenschaft vor.
type: docs
weight: 480
url: /de/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Die CSSPrimitiveValue-Schnittstelle repräsentiert einen einzelnen CSS-Wert. Diese Schnittstelle kann verwendet werden, um den Wert einer bestimmten Stileigenschaft zu bestimmen, die derzeit in einem Block festgelegt ist, oder um eine bestimmte Stileigenschaft explizit innerhalb des Blocks festzulegen. Eine Instanz dieser Schnittstelle kann von der getPropertyCSSValue-Methode der CSSStyleDeclaration-Schnittstelle abgerufen werden. Ein CSSPrimitiveValue-Objekt kommt nur im Kontext einer CSS-Eigenschaft vor.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | Eine Zeichenfolgendarstellung des aktuellen Werts. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Ein Code, der den Werttyp definiert. |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | Der Typ des Werts, wie er durch die oben angegebenen Konstanten definiert ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(object) | Bestimmt, ob die angegebeneObject ist gleich dieser Instanz. |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | Diese Methode wird verwendet, um den Zählerwert zu erhalten. Wenn dieser CSS-Wert keinen Zählerwert enthält, wird eine DOMException ausgelöst. Die Änderung der entsprechenden Stileigenschaft kann über die Counter-Schnittstelle erreicht werden. |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Diese Methode wird verwendet, um einen Gleitkommawert in einer bestimmten Einheit zu erhalten. Wenn dieser CSS-Wert keinen Float-Wert enthält oder nicht in die angegebene Einheit konvertiert werden kann, wird eine DOMException ausgelöst. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Gibt einen Hash-Code für diese Instanz zurück. |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Diese Methode wird verwendet, um einen int-Wert in einer bestimmten Einheit zu erhalten. Wenn dieser CSS-Wert keinen int-Wert enthält oder nicht in die angegebene Einheit konvertiert werden kann, wird eine DOMException ausgelöst. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | Diese Methode wird verwendet, um den Rect-Wert zu erhalten. Wenn dieser CSS-Wert keinen Rect-Wert enthält, wird eine DOMException ausgelöst. Die Änderung der entsprechenden Stileigenschaft kann über die Rect-Schnittstelle erreicht werden. |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Diese Methode wird verwendet, um die RGB-Farbe zu erhalten. Wenn dieser CSS-Wert keinen RGB-Farbwert enthält, wird eine DOMException ausgelöst. Die Änderung der entsprechenden Stileigenschaft kann mit der RGBColor-Schnittstelle erreicht werden. |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | Diese Methode wird verwendet, um den Zeichenfolgenwert abzurufen. Wenn der CSS-Wert keinen Zeichenfolgenwert enthält, wird eine DOMException ausgelöst. |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Eine Methode, um den Gleitkommawert mit einer bestimmten Einheit zu setzen. Wenn die mit diesem Wert verknüpfte Eigenschaft die angegebene Einheit oder den Gleitkommawert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Eine Methode, um den int-Wert mit einer bestimmten Einheit zu setzen. Wenn die mit diesem Wert verknüpfte Eigenschaft die angegebene Einheit oder den int-Wert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | Eine Methode, um den Stringwert mit der angegebenen Einheit zu setzen. Wenn die an diesen Wert angehängte Eigenschaft die angegebene Einheit oder den Zeichenfolgenwert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | Der Wert ist eine Attributfunktion. Der Wert kann mithilfe der getStringValue-Methode abgerufen werden. |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | Der Wert ist eine Länge (ch). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | Der Wert ist eine Länge (cm). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | Der Wert ist ein Zähler oder eine Zählerfunktion. Der Wert kann mithilfe der GetCounterValue-Methode abgerufen werden. |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | Der Wert ist ein Winkel (Grad). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | Der Wert ist eine Zahl mit unbekannter Dimension. Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | Der Wert ist ein Punkt pro Zentimeter (dpcm). |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | Der Wert ist Punkte pro Zoll (dpi). |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | Der Wert ist ein Punkt pro 'px'-Einheit (dppx). |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | Der Wert ist eine Länge (ems). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | Der Wert ist eine Länge (exs). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | Der Wert ist ein Winkel (Grad). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | Der Wert ist eine Frequenz (Hz). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | Der Wert ist ein Bezeichner. Der Wert kann mithilfe der getStringValue-Methode abgerufen werden. |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | Der Wert ist eine Länge (in). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | Der Wert ist eine Frequenz (kHz). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | Der Wert ist eine Länge (mm). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | Der Wert ist eine Zeit (ms). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | Der Wert ist eine einfache Zahl. Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | Der Wert ist eine Länge (pc). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | Der Wert ist ein Prozentsatz. Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | Der Wert ist eine Länge (pt). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | Der Wert ist eine Länge (px). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | Der Wert ist ein Winkel (rad). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | Der Wert ist eine Rechteckfunktion. Der Wert kann mithilfe der GetRectValue-Methode abgerufen werden. |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | Der Wert ist eine Länge (rem). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | Der Wert ist eine RGB-Farbe. Der Wert kann mithilfe der GetRGBColorValue-Methode abgerufen werden. |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | Der Wert ist eine Zeit (s). Der Wert kann mit der getFloatValue-Methode abgerufen werden. |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | Der Wert ist ein STRING. Der Wert kann mithilfe der getStringValue-Methode abgerufen werden. |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | Der Wert ist kein anerkannter CSS2-Wert. Der Wert kann nur über das cssText-Attribut abgerufen werden. |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | Der Wert ist ein URI. Der Wert kann mithilfe der getStringValue-Methode abgerufen werden. |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | Der Wert ist ein Prozentsatz der vollen Darstellungshöhe. |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | Der Wert ist ein Prozentsatz der Breite oder Höhe des Ansichtsfensters, je nachdem, welcher Wert größer ist. |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | Der Wert ist ein Prozentsatz der Breite oder Höhe des Ansichtsfensters, je nachdem, welcher Wert kleiner ist. |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | Der Wert ist ein Prozentsatz der vollen Ansichtsfensterbreite. |

### Siehe auch

* class [CSSValue](../cssvalue/)
* namensraum [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* Montage [Aspose.SVG](../../)


