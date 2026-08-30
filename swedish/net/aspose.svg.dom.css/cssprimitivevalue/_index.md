---
title: "CSSPrimitiveValue-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.CSSPrimitiveValue class. CSSPrimitiveValue‑gränssnittet representerar ett enskilt CSS‑värde. Detta gränssnitt kan användas för att bestämma värdet på en specifik stil‑egenskap som för närvarande är satt i ett block eller för att explicit sätta en specifik stil‑egenskap inom blocket. En instans av detta gränssnitt kan erhållas via getPropertyCSSValue‑metoden i CSSStyleDeclaration‑gränssnittet. Ett CSSPrimitiveValue‑objekt förekommer endast i samband med en CSS‑egenskap."
type: docs
weight: 2480
url: /sv/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue-gränssnittet representerar ett enskilt CSS‑värde. Detta gränssnitt kan användas för att bestämma värdet på en specifik stil‑egenskap som för närvarande är satt i ett block eller för att explicit sätta en specifik stil‑egenskap inom blocket. En instans av detta gränssnitt kan erhållas via getPropertyCSSValue‑metoden i CSSStyleDeclaration‑gränssnittet. Ett CSSPrimitiveValue‑objekt förekommer endast i samband med en CSS‑egenskap.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | CSSText-egenskapen i [`CSSValue`](../cssvalue/)-gränssnittet representerar det aktuella beräknade CSS-egenskapsvärdet. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | En kod som definierar värdets typ. |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | Typen av värdet enligt de konstanter som specificerats ovan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bestämmer om det angivna Object är lika med den här instansen. |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | Denna metod används för att hämta Counter‑värdet. Om detta CSS‑värde inte innehåller ett counter‑värde kastas ett DOMException. Ändring av motsvarande stil‑egenskap kan göras med Counter‑gränssnittet. |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(*ushort*) | Denna metod används för att hämta ett flyttal‑värde i en specificerad enhet. Om detta CSS‑värde inte innehåller ett flyttal‑värde eller inte kan konverteras till den specificerade enheten kastas ett DOMException. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Returnerar en hashkod för den här instansen. |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(*ushort*) | Denna metod används för att hämta ett heltals‑värde i en specificerad enhet. Om detta CSS‑värde inte innehåller ett heltals‑värde eller inte kan konverteras till den specificerade enheten kastas ett DOMException. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objekttyp. |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | Denna metod används för att hämta Rect‑värdet. Om detta CSS‑värde inte innehåller ett rect‑värde kastas ett DOMException. Ändring av motsvarande stil‑egenskap kan göras med Rect‑gränssnittet. |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Denna metod används för att hämta RGB-färgen. Om detta CSS-värde inte innehåller ett RGB-färgvärde, kastas ett DOMException. Ändring av motsvarande stil-egenskap kan uppnås med hjälp av RGBColor-gränssnittet. |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | Denna metod används för att hämta strängvärdet. Om CSS-värdet inte innehåller ett strängvärde, kastas ett DOMException. |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(*ushort, float*) | En metod för att sätta flyttalsvärdet med en specificerad enhet. Om egenskapen som är kopplad till detta värde inte kan acceptera den specificerade enheten eller flyttalsvärdet, förblir värdet oförändrat och ett DOMException kastas. |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(*ushort, int*) | En metod för att sätta heltalsvärdet med en specificerad enhet. Om egenskapen som är kopplad till detta värde inte kan acceptera den specificerade enheten eller heltalsvärdet, förblir värdet oförändrat och ett DOMException kastas. |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(*ushort, string*) | En metod för att sätta strängvärdet med den specificerade enheten. Om egenskapen som är kopplad till detta värde inte kan acceptera den specificerade enheten eller strängvärdet, förblir värdet oförändrat och ett DOMException kastas. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Returnerar en sträng som representerar den här instansen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | Värdet är en attributfunktion. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | Värdet är en längd (ch). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | Värdet är en längd (cm). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | Värdet är en counter- eller counters-funktion. Värdet kan erhållas genom att använda metoden GetCounterValue. |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | Värdet är en vinkel (deg). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | Värdet är ett tal med en okänd dimension. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | Värdet är punkter per centimeter (dpcm). |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | Värdet är punkter per tum (dpi). |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | Värdet är punkter per ‘px’-enhet (dppx). |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | Värdet är en längd (ems). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | Värdet är en längd (exs). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_FR](../../aspose.svg.dom.css/cssprimitivevalue/css_fr/) | En flexibel längd eller flex är en dimension med enheten fr, som representerar en bråkdel av det återstående utrymmet i rutnätsbehållaren. |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | Värdet är en vinkel (grad). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | Värdet är en frekvens (Hz). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | Värdet är en identifierare. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | Värdet är en längd (in). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | Värdet är en frekvens (kHz). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | Värdet är en längd (mm). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | Värdet är en tid (ms). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | Värdet är ett enkelt tal. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | Värdet är en längd (pc). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | Värdet är en procentandel. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | Värdet är en längd (pt). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | Värdet är en längd (px). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | Värdet är en vinkel (rad). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | Värdet är en rect-funktion. Värdet kan erhållas genom att använda metoden GetRectValue. |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | Värdet är en längd (rem). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | Värdet är en RGB-färg. Värdet kan erhållas genom att använda metoden GetRGBColorValue. |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | Värdet är en tid (s). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | Värdet är en STRÄNG. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | Värdet är inte ett känt CSS2‑värde. Värdet kan endast erhållas genom att använda attributet cssText. |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | Värdet är en URI. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | Värdet är en procentandel av hela visningsportens höjd. |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | Värdet är en procentandel av visningsportens bredd eller höjd, beroende på vilket som är störst. |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | Värdet är en procentandel av visningsportens bredd eller höjd, beroende på vilket som är minst. |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | Värdet är en procentandel av hela visningsportens bredd. |
| const [CSS_X](../../aspose.svg.dom.css/cssprimitivevalue/css_x/) | Värdet är en punkter per ‘px’-enhet (x). |

### Se även

* class [CSSValue](../cssvalue/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
