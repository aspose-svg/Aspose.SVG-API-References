---
title: "CSSPrimitiveValue Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.CSSPrimitiveValue Klasse. Die CSSPrimitiveValue‑Schnittstelle repräsentiert einen einzelnen CSS‑Wert. Diese Schnittstelle kann verwendet werden, um den Wert einer bestimmten Stil‑Eigenschaft zu bestimmen, die derzeit in einem Block gesetzt ist, oder um eine bestimmte Stil‑Eigenschaft explizit innerhalb des Blocks zu setzen. Eine Instanz dieser Schnittstelle kann über die getPropertyCSSValue‑Methode der CSSStyleDeclaration‑Schnittstelle erhalten werden. Ein CSSPrimitiveValue‑Objekt tritt nur im Kontext einer CSS‑Eigenschaft auf."
type: docs
weight: 2480
url: /de/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Das CSSPrimitiveValue-Interface repräsentiert einen einzelnen CSS‑Wert. Dieses Interface kann verwendet werden, um den Wert einer bestimmten Style‑Property, die derzeit in einem Block gesetzt ist, zu bestimmen oder um eine bestimmte Style‑Property explizit innerhalb des Blocks zu setzen. Eine Instanz dieses Interfaces kann über die getPropertyCSSValue‑Methode des CSSStyleDeclaration-Interfaces erhalten werden. Ein CSSPrimitiveValue‑Objekt tritt nur im Kontext einer CSS‑Property auf.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | Die CSSText‑Eigenschaft der [`CSSValue`](../cssvalue/) Schnittstelle stellt den aktuell berechneten CSS‑Eigenschaftswert dar. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Ein Code, der den Typ des Werts definiert. |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | Der Typ des Wertes, wie durch die oben angegebenen Konstanten definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | Diese Methode wird verwendet, um den Counter‑Wert zu erhalten. Wenn dieser CSS‑Wert keinen Counter‑Wert enthält, wird eine DOMException ausgelöst. Änderungen an der entsprechenden Stil‑Eigenschaft können über die Counter‑Schnittstelle vorgenommen werden. |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(*ushort*) | Diese Methode wird verwendet, um einen Float‑Wert in einer angegebenen Einheit zu erhalten. Wenn dieser CSS‑Wert keinen Float‑Wert enthält oder nicht in die angegebene Einheit konvertiert werden kann, wird eine DOMException ausgelöst. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(*ushort*) | Diese Methode wird verwendet, um einen int-Wert in einer angegebenen Einheit zu erhalten. Wenn dieser CSS-Wert keinen int-Wert enthält oder nicht in die angegebene Einheit konvertiert werden kann, wird eine DOMException ausgelöst. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | Diese Methode wird verwendet, um den Rect-Wert zu erhalten. Wenn dieser CSS-Wert keinen Rect-Wert enthält, wird eine DOMException ausgelöst. Änderungen an der entsprechenden Style-Eigenschaft können über die Rect-Schnittstelle vorgenommen werden. |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Diese Methode wird verwendet, um die RGB-Farbe zu erhalten. Wenn dieser CSS-Wert keinen RGB-Farbwert enthält, wird eine DOMException ausgelöst. Änderungen an der entsprechenden Style-Eigenschaft können über die RGBColor-Schnittstelle vorgenommen werden. |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | Diese Methode wird verwendet, um den Zeichenkettenwert zu erhalten. Wenn der CSS-Wert keinen Zeichenkettenwert enthält, wird eine DOMException ausgelöst. |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(*ushort, float*) | Eine Methode, um den Float-Wert mit einer angegebenen Einheit zu setzen. Wenn die mit diesem Wert verbundene Eigenschaft die angegebene Einheit oder den Float-Wert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(*ushort, int*) | Eine Methode, um den int-Wert mit einer angegebenen Einheit zu setzen. Wenn die mit diesem Wert verbundene Eigenschaft die angegebene Einheit oder den int-Wert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(*ushort, string*) | Eine Methode, um den Zeichenkettenwert mit der angegebenen Einheit zu setzen. Wenn die mit diesem Wert verbundene Eigenschaft die angegebene Einheit oder den Zeichenkettenwert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | Der Wert ist eine Attributfunktion. Der Wert kann mit der Methode getStringValue abgerufen werden. |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | Der Wert ist eine Länge (ch). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | Der Wert ist eine Länge (cm). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | Der Wert ist eine counter- oder counters-Funktion. Der Wert kann mit der Methode GetCounterValue abgerufen werden. |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | Der Wert ist ein Winkel (deg). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | Der Wert ist eine Zahl mit unbekannter Dimension. Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | Der Wert ist ein Punkt pro Zentimeter (dpcm). |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | Der Wert ist ein Punkt pro Zoll (dpi). |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | Der Wert ist ein Punkt pro ‘px’-Einheit (dppx). |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | Der Wert ist eine Länge (ems). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | Der Wert ist eine Länge (exs). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_FR](../../aspose.svg.dom.css/cssprimitivevalue/css_fr/) | Eine flexible Länge oder Flex ist eine Dimension mit der Einheit fr, die einen Bruchteil des verbleibenden Raums im Grid-Container darstellt. |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | Der Wert ist ein Winkel (grad). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | Der Wert ist eine Frequenz (Hz). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | Der Wert ist ein Bezeichner. Der Wert kann mit der Methode getStringValue abgerufen werden. |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | Der Wert ist eine Länge (in). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | Der Wert ist eine Frequenz (kHz). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | Der Wert ist eine Länge (mm). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | Der Wert ist eine Zeit (ms). Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | Der Wert ist eine einfache Zahl. Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | Der Wert ist eine Länge (pc). Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | Der Wert ist ein Prozentsatz. Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | Der Wert ist eine Länge (pt). Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | Der Wert ist eine Länge (px). Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | Der Wert ist ein Winkel (rad). Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | Der Wert ist eine rect-Funktion. Der Wert kann durch die Verwendung der Methode GetRectValue ermittelt werden. |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | Der Wert ist eine Länge (rem). Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | Der Wert ist eine RGB-Farbe. Der Wert kann durch die Verwendung der Methode GetRGBColorValue ermittelt werden. |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | Der Wert ist eine Zeit (s). Der Wert kann durch die Verwendung der Methode getFloatValue ermittelt werden. |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | Der Wert ist ein STRING. Der Wert kann durch die Verwendung der Methode getStringValue ermittelt werden. |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | Der Wert ist kein erkannter CSS2-Wert. Der Wert kann nur durch die Verwendung des Attributs cssText ermittelt werden. |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | Der Wert ist ein URI. Der Wert kann durch die Verwendung der Methode getStringValue ermittelt werden. |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | Der Wert ist ein Prozentsatz der vollen Viewport-Höhe. |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | Der Wert ist ein Prozentsatz der Viewport-Breite oder -Höhe, je nachdem, welcher größer ist. |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | Der Wert ist ein Prozentsatz der Viewport-Breite oder -Höhe, je nachdem, welcher kleiner ist. |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | Der Wert ist ein Prozentsatz der vollen Viewport-Breite. |
| const [CSS_X](../../aspose.svg.dom.css/cssprimitivevalue/css_x/) | Der Wert ist ein Punkt pro ‘px’-Einheit (x). |

### Siehe auch

* class [CSSValue](../cssvalue/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
