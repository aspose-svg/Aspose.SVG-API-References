---
title: "CSSPrimitiveValue class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.CSSPrimitiveValue class. De CSSPrimitiveValue-interface vertegenwoordigt een enkele CSS-waarde. Deze interface kan worden gebruikt om de waarde van een specifieke stijl-eigenschap die momenteel in een blok is ingesteld te bepalen, of om een specifieke stijl-eigenschap expliciet binnen het blok in te stellen. Een instantie van deze interface kan worden verkregen via de getPropertyCSSValue-methode van de CSSStyleDeclaration-interface. Een CSSPrimitiveValue-object komt alleen voor in de context van een CSS-eigenschap."
type: docs
weight: 2480
url: /nl/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

De CSSPrimitiveValue interface vertegenwoordigt een enkele CSS‑waarde. Deze interface kan worden gebruikt om de waarde van een specifieke stijl‑eigenschap die momenteel in een blok is ingesteld te bepalen, of om een specifieke stijl‑eigenschap expliciet binnen het blok in te stellen. Een instantie van deze interface kan worden verkregen via de getPropertyCSSValue‑methode van de CSSStyleDeclaration interface. Een CSSPrimitiveValue‑object komt alleen voor in de context van een CSS‑eigenschap.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | De CSSText-eigenschap van de [`CSSValue`](../cssvalue/) interface vertegenwoordigt de momenteel berekende CSS-eigenschapswaarde. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Een code die het type van de waarde definieert. |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | Het type van de waarde zoals gedefinieerd door de hierboven gespecificeerde constanten. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | Deze methode wordt gebruikt om de Counter-waarde op te halen. Als deze CSS-waarde geen counter-waarde bevat, wordt een DOMException opgegooid. Aanpassing van de overeenkomstige stijl-eigenschap kan worden bereikt met behulp van de Counter-interface. |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(*ushort*) | Deze methode wordt gebruikt om een float-waarde op te halen in een opgegeven eenheid. Als deze CSS-waarde geen float-waarde bevat of niet kan worden omgezet naar de opgegeven eenheid, wordt een DOMException opgegooid. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Retourneert een hashcode voor deze instantie. |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(*ushort*) | Deze methode wordt gebruikt om een int-waarde op te halen in een opgegeven eenheid. Als deze CSS-waarde geen int-waarde bevat of niet kan worden omgezet naar de opgegeven eenheid, wordt een DOMException opgegooid. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | Deze methode wordt gebruikt om de Rect-waarde op te halen. Als deze CSS-waarde geen rect-waarde bevat, wordt een DOMException opgegooid. Aanpassing van de overeenkomstige stijl-eigenschap kan worden bereikt met behulp van de Rect-interface. |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Deze methode wordt gebruikt om de RGB-kleur op te halen. Als deze CSS-waarde geen RGB-kleurwaarde bevat, wordt een DOMException opgegooid. Aanpassing van de overeenkomstige stijl-eigenschap kan worden bereikt met behulp van de RGBColor-interface. |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | Deze methode wordt gebruikt om de stringwaarde op te halen. Als de CSS-waarde geen stringwaarde bevat, wordt een DOMException opgegooid. |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(*ushort, float*) | Een methode om de float-waarde in te stellen met een opgegeven eenheid. Als de eigenschap die aan deze waarde is gekoppeld de opgegeven eenheid of de float-waarde niet kan accepteren, blijft de waarde ongewijzigd en wordt een DOMException opgegooid. |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(*ushort, int*) | Een methode om de int-waarde in te stellen met een opgegeven eenheid. Als de eigenschap die aan deze waarde is gekoppeld de opgegeven eenheid of de int-waarde niet kan accepteren, blijft de waarde ongewijzigd en wordt er een DOMException opgegooid. |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(*ushort, string*) | Een methode om de stringwaarde in te stellen met de opgegeven eenheid. Als de eigenschap die aan deze waarde is gekoppeld de opgegeven eenheid of de stringwaarde niet kan accepteren, blijft de waarde ongewijzigd en wordt er een DOMException opgegooid. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | De waarde is een attribuutfunctie. De waarde kan worden verkregen met de methode getStringValue. |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | De waarde is een lengte (ch). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | De waarde is een lengte (cm). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | De waarde is een teller- of tellersfunctie. De waarde kan worden verkregen met de methode GetCounterValue. |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | De waarde is een hoek (deg). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | De waarde is een getal met een onbekende dimensie. De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | De waarde is punten per centimeter (dpcm). |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | De waarde is punten per inch (dpi). |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | De waarde is punten per ‘px’-eenheid (dppx). |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | De waarde is een lengte (ems). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | De waarde is een lengte (exs). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_FR](../../aspose.svg.dom.css/cssprimitivevalue/css_fr/) | Een flexibele lengte of flex is een dimensie met de fr-eenheid, die een fractie van de resterende ruimte in de rastercontainer vertegenwoordigt. |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | De waarde is een hoek (grad). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | De waarde is een frequentie (Hz). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | De waarde is een identifier. De waarde kan worden verkregen met de methode getStringValue. |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | De waarde is een lengte (in). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | De waarde is een frequentie (kHz). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | De waarde is een lengte (mm). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | De waarde is een tijd (ms). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | De waarde is een eenvoudig getal. De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | De waarde is een lengte (pc). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | De waarde is een percentage. De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | De waarde is een lengte (pt). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | De waarde is een lengte (px). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | De waarde is een hoek (rad). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | De waarde is een rect-functie. De waarde kan worden verkregen door de GetRectValue-methode te gebruiken. |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | De waarde is een lengte (rem). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | De waarde is een RGB-kleur. De waarde kan worden verkregen door de GetRGBColorValue-methode te gebruiken. |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | De waarde is een tijd (s). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | De waarde is een STRING. De waarde kan worden verkregen door de getStringValue-methode te gebruiken. |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | De waarde is geen erkende CSS2-waarde. De waarde kan alleen worden verkregen door het cssText-attribuut te gebruiken. |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | De waarde is een URI. De waarde kan worden verkregen door de getStringValue-methode te gebruiken. |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | De waarde is een percentage van de volledige viewport-hoogte. |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | De waarde is een percentage van de viewport-breedte of -hoogte, afhankelijk van welke groter is. |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | De waarde is een percentage van de viewport-breedte of -hoogte, afhankelijk van welke kleiner is. |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | De waarde is een percentage van de volledige viewport-breedte. |
| const [CSS_X](../../aspose.svg.dom.css/cssprimitivevalue/css_x/) | De waarde is een punten per ‘px’-eenheid (x). |

### Zie ook

* class [CSSValue](../cssvalue/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
