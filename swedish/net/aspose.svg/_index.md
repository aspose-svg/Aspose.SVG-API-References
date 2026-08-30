---
title: "Aspose.Svg"
second_title: "Aspose.SVG för .NET API-referens"
description: "Alla klasser i Aspose.Svg.Dom.Svg‑namnutrymmet är baserade på w3c SVG2‑rekommendationer. Genom att använda detta namnrymd kan du ladda, navigera eller rendera SVG‑filen enligt dina krav."
type: docs
weight: 10
url: /sv/net/aspose.svg/
---
Alla klasser i **Aspose.Svg.Dom.Svg** namnrymd är baserade på w3c SVG2-rekommendationer. Med hjälp av denna namnrymd kan du ladda, navigera eller rendera SVG-filen enligt dina krav.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Configuration](./configuration/) | Representerar kontextobjektet för konfiguration som används för att ställa in miljöinställningarna för applikationen. |
| [FontsSettings](./fontssettings/) | Representerar inställningar för teckensnittshantering. |
| [License](./license/) | Tillhandahåller metoder för att licensiera komponenten. |
| [Metered](./metered/) | Tillhandahåller metoder för att ange mätad nyckel. |
| [MimeType](./mimetype/) | Representerar en Internet Media Type |
| [PlatformException](./platformexception/) | Representerar basklassen för alla undantag som kan uppstå under applikationens körning. |
| [SVGAElement](./svgaelement/) | SVGAElement‑gränssnittet motsvarar ‘a’-elementet. |
| [SVGAnimateElement](./svganimateelement/) | SVGAnimateElement‑gränssnittet motsvarar ‘animate’-elementet. Objektorienterad åtkomst till attributen för ‘animate’-elementet via SVG‑DOM är inte tillgänglig. |
| [SVGAnimateMotionElement](./svganimatemotionelement/) | SVGAnimateMotionElement‑gränssnittet motsvarar ‘animateMotion’-elementet. Objektorienterad åtkomst till attributen för ‘animateMotion’-elementet via SVG‑DOM är inte tillgänglig. |
| [SVGAnimateTransformElement](./svganimatetransformelement/) | SVGAnimateTransformElement‑gränssnittet motsvarar ‘animateTransform’-elementet. Objektorienterad åtkomst till attributen för ‘animateTransform’-elementet via SVG‑DOM är inte tillgänglig. |
| [SVGAnimationElement](./svganimationelement/) | SVGAnimationElement‑gränssnittet är basgränssnittet för alla animations‑elementgränssnitt: SVGAnimateElement, SVGSetElement, SVGAnimateColorElement, SVGAnimateMotionElement och SVGAnimateTransformElement. |
| [SVGCircleElement](./svgcircleelement/) | SVGCircleElement‑gränssnittet motsvarar ‘circle’-elementet. |
| [SVGClipPathElement](./svgclippathelement/) | SVGClipPathElement‑gränssnittet motsvarar ‘clipPath’-elementet. |
| [SVGComponentTransferFunctionElement](./svgcomponenttransferfunctionelement/) | Detta gränssnitt definierar ett basgränssnitt som används av komponentens överföringsfunktionsgränssnitt. |
| [SVGCursorElement](./svgcursorelement/) | SVGCursorElement‑gränssnittet motsvarar ‘cursor’-elementet. |
| [SVGDefsElement](./svgdefselement/) | SVGDefsElement‑gränssnittet motsvarar ‘defs’-elementet. |
| [SVGDescElement](./svgdescelement/) | SVGDescElement‑gränssnittet motsvarar ‘desc’-elementet. |
| [SVGDocument](./svgdocument/) | Ett `SVGDocument` är roten i SVG‑hierarkin och innehåller hela innehållet. Förutom att ge åtkomst till hierarkin tillhandahåller det även några bekvämlighetsmetoder för att komma åt vissa informationsuppsättningar från dokumentet. Förutom att läsa in standard‑.svg‑filer kan både konstruktorerna och [`Navigate`](../aspose.svg.dom/document/navigate/)‑metoden läsa in gzip‑komprimerade .svgz‑filer. När ett ‘svg’-element bäddas in inline som en komponent i ett dokument från ett annat namnrymd, till exempel när ett ‘svg’-element bäddas in inline i ett XHTML‑dokument [XHTML], kommer ett SVGDocument‑objekt inte att finnas; istället blir rotobjektet i dokumentobjekthierarkin ett Document‑objekt av en annan typ, såsom ett HTMLDocument‑objekt. Ett SVGDocument‑objekt kommer dock att finnas när rot‑elementet i XML‑dokumenthierarkin är ett ‘svg’-element, till exempel när man visar en fristående SVG‑fil (dvs. en fil med MIME‑typen "image/svg+xml"). I så fall blir SVGDocument‑objektet rotobjektet i dokumentobjektmodellens hierarki. |
| [SVGElement](./svgelement/) | Alla SVG‑DOM‑gränssnitt som motsvarar element i SVG‑språket direkt (t.ex. SVGPathElement‑gränssnittet för ‘path’-elementet) ärver från SVGElement‑gränssnittet. |
| [SVGElementInstance](./svgelementinstance/) | Rotobjektet för varje use-element skuggträd implementerar gränssnittet SVGUseElementShadowRoot. Detta gränssnitt definierar för närvarande inga utökningar av egenskaperna och metoderna som definieras för gränssnittet ShadowRoot och mixinen DocumentOrShadowRoot. Däremot är trädet som är rotat vid denna nod helt skrivskyddat ur författarskriptens perspektiv. |
| [SVGEllipseElement](./svgellipseelement/) | Gränssnittet SVGEllipseElement motsvarar elementet ‘ellipse’. |
| [SVGException](./svgexception/) | Detta undantag kastas när en specifik SVG‑operation är omöjlig att utföra. |
| [SVGFilterElement](./svgfilterelement/) | Gränssnittet SVGFilterElement motsvarar elementet ‘filter’. |
| [SVGForeignObjectElement](./svgforeignobjectelement/) | Gränssnittet SVGForeignObjectElement motsvarar elementet ‘foreignObject’. |
| [SVGGElement](./svggelement/) | Gränssnittet SVGGElement motsvarar elementet ‘g’. |
| [SVGGeometryElement](./svggeometryelement/) | Gränssnittet SVGGeometryElement representerar SVG‑element vars rendering definieras av geometri med en motsvarande bana, och som kan fyllas och kontureras. Detta inkluderar banor och de grundläggande formerna. |
| [SVGGradientElement](./svggradientelement/) | Gränssnittet SVGGradientElement är ett basgränssnitt som används av SVGLinearGradientElement och SVGRadialGradientElement. |
| [SVGGraphicsElement](./svggraphicselement/) | Gränssnittet SVGGraphicsElement representerar SVG‑element vars primära syfte är att direkt rendera grafik i en grupp. |
| [SVGImageElement](./svgimageelement/) | Gränssnittet SVGImageElement motsvarar elementet ‘image’. |
| [SVGLinearGradientElement](./svglineargradientelement/) | Gränssnittet SVGLinearGradientElement motsvarar elementet ‘linearGradient’. |
| [SVGLineElement](./svglineelement/) | Gränssnittet SVGLineElement motsvarar elementet ‘line’. |
| [SVGMarkerElement](./svgmarkerelement/) | Gränssnittet SVGMarkerElement motsvarar elementet ‘marker’. |
| [SVGMaskElement](./svgmaskelement/) | Gränssnittet SVGMaskElement motsvarar elementet ‘mask’. |
| [SVGMetadataElement](./svgmetadataelement/) | Gränssnittet SVGMetadataElement motsvarar elementet ‘metadata’. |
| [SVGMPathElement](./svgmpathelement/) | Gränssnittet SVGMPathElement motsvarar elementet ‘mpath’. |
| [SVGPathElement](./svgpathelement/) | Gränssnittet SVGPathElement motsvarar elementet ‘path’. |
| [SVGPatternElement](./svgpatternelement/) | Gränssnittet SVGPatternElement motsvarar elementet ‘pattern’. |
| [SVGPolygonElement](./svgpolygonelement/) | Gränssnittet SVGPolygonElement motsvarar elementet ‘polygon’. |
| [SVGPolylineElement](./svgpolylineelement/) | Gränssnittet SVGPolylineElement motsvarar elementet ‘polyline’. |
| [SVGRadialGradientElement](./svgradialgradientelement/) | Gränssnittet SVGRadialGradientElement motsvarar elementet ‘radialGradient’. |
| [SVGRectElement](./svgrectelement/) | Gränssnittet SVGRectElement motsvarar elementet ‘rect’. |
| [SVGScriptElement](./svgscriptelement/) | Gränssnittet SVGScriptElement motsvarar elementet ‘script’. |
| [SVGSetElement](./svgsetelement/) | Gränssnittet SVGSetElement motsvarar elementet ‘set’. Objektorienterad åtkomst till attributen för ‘set’-elementet via SVG‑DOM är inte tillgänglig. |
| [SVGStopElement](./svgstopelement/) | Gränssnittet SVGStopElement motsvarar elementet ‘stop’. |
| [SVGStyleElement](./svgstyleelement/) | SVGStyleElement‑gränssnittet motsvarar ‘style’-elementet. |
| [SVGSVGElement](./svgsvgelement/) | En viktig gränssnittsdefinition är SVGSVGElement‑gränssnittet, som är gränssnittet som motsvarar ‘svg’-elementet. Detta gränssnitt innehåller olika diverse ofta använda verktygsmetoder, såsom matrisoperationer och möjligheten att kontrollera omritningstiden på visuella renderingsenheter. |
| [SVGSwitchElement](./svgswitchelement/) | SVGSwitchElement‑gränssnittet motsvarar ‘switch’-elementet. |
| [SVGSymbolElement](./svgsymbolelement/) | SVGSymbolElement‑gränssnittet motsvarar ‘symbol’-elementet. |
| [SVGTextContentElement](./svgtextcontentelement/) | SVGTextContentElement ärvs av olika textrelaterade gränssnitt, såsom SVGTextElement, SVGTSpanElement, SVGTRefElement, SVGAltGlyphElement och SVGTextPathElement. För metoderna i detta gränssnitt som refererar till ett index till ett tecken eller ett antal tecken, ska dessa referenser tolkas som ett index till en UTF‑16‑kodenhet eller ett antal UTF‑16‑kodenheter, respektive. Detta görs för att vara i enlighet med DOM Level 2 Core, där metoderna i CharacterData‑gränssnittet använder UTF‑16‑kodenheter som index och räknare inom teckendatan. Så till exempel, om textinnehållet i ett ‘text’-element är ett enda icke‑BMP‑tecken, såsom U+10000, så kommer anrop av getNumberOfChars på det elementet att returnera 2 eftersom två UTF‑16‑kod­enheter (surrogatparet) används för att representera det tecknet. |
| [SVGTextElement](./svgtextelement/) | SVGTextElement‑gränssnittet motsvarar ‘text’-elementet. |
| [SVGTextPathElement](./svgtextpathelement/) | SVGTextPathElement‑gränssnittet motsvarar ‘textPath’-elementet. |
| [SVGTextPositioningElement](./svgtextpositioningelement/) | SVGTextPositioningElement‑gränssnittet ärvs av textrelaterade gränssnitt: SVGTextElement, SVGTSpanElement, SVGTRefElement och SVGAltGlyphElement. |
| [SVGTitleElement](./svgtitleelement/) | SVGTitleElement‑gränssnittet motsvarar ‘title’-elementet. |
| [SVGTSpanElement](./svgtspanelement/) | SVGTSpanElement‑gränssnittet motsvarar ‘tspan’-elementet. |
| [SVGUseElement](./svguseelement/) | SVGUseElement‑gränssnittet motsvarar ‘use’-elementet. |
| [SVGViewElement](./svgviewelement/) | SVGViewElement‑gränssnittet motsvarar ‘view’-elementet. |
| [Url](./url/) | Tillhandahåller en objektrepresentation av en universell identifierare (URL). |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IConfigurationBuilder](./iconfigurationbuilder/) | Representerar en byggare för Configuration‑objekt. |
| [IConfigurationExtension](./iconfigurationextension/) | Representerar ett tillägg för konfiguration, som möjliggör tillägg och hämtning av nyckel‑värde‑par. |
| [ISVGAnimatedPoints](./isvganimatedpoints/) | SVGAnimatedPoints‑gränssnittet stödjer element som har ett ‘points’-attribut som innehåller en lista med koordinatvärden och som möjliggör att animera det attributet. Dessutom kommer ‘points’-attributet på det ursprungliga elementet som nås via XML‑DOM (t.ex. med getAttribute()-metodanrop) att återspegla alla ändringar som gjorts i points. |
| [ISVGFitToViewBox](./isvgfittoviewbox/) | Gränssnittet SVGFitToViewBox definierar DOM‑attribut som gäller för element som har XML‑attributen ‘viewBox’ och ‘preserveAspectRatio’. |
| [ISVGRenderingIntent](./isvgrenderingintent/) | SVGRenderingIntent‑gränssnittet definierar den uppräknade listan av möjliga värden för ‘rendering-intent’-attribut eller -beskrivare. |
| [ISVGTests](./isvgtests/) | Gränssnittet SVGTests definierar ett gränssnitt som gäller för alla element som har attributen ‘requiredFeatures’, ‘requiredExtensions’ och ‘systemLanguage’. |
| [ISVGUnitTypes](./isvgunittypes/) | SVGUnitTypes‑gränssnittet definierar en vanligt använd uppsättning konstanter och är ett basgränssnitt som används av SVGGradientElement, SVGPatternElement, SVGClipPathElement, SVGMaskElement och SVGFilterElement. |
| [ISVGURIReference](./isvgurireference/) | Gränssnittet SVGURIReference definierar ett gränssnitt som gäller för alla element som har samlingen av XLink‑attribut, såsom ‘xlink:href’, som definierar en URI‑referens. |
| [ISVGZoomAndPan](./isvgzoomandpan/) | SVGZoomAndPan‑gränssnittet definierar attributet zoomAndPan och tillhörande konstanter. |
| [IUrlSearchParams](./iurlsearchparams/) | Tillhandahåller metoder för att arbeta med URL‑frågesträng. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [Sandbox](./sandbox/) | En sandbox‑flaggsats är en uppsättning av noll eller fler av följande flaggor, som används för att begränsa de förmågor som potentiellt opålitliga resurser har. |
| [SVGRenderingIntent](./svgrenderingintent/) | SVGRenderingIntent‑enumerationen definierar den uppräknade listan av möjliga värden för ‘rendering-intent’-attribut eller -beskrivare. |
| [SVGUnitTypes](./svgunittypes/) | SVGUnitTypes‑enumerationen definierar en vanligt använd uppsättning konstanter och är ett basgränssnitt som används av SVGGradientElement, SVGPatternElement, SVGClipPathElement, SVGMaskElement och SVGFilterElement. |
| [SVGZoomAndPan](./svgzoomandpan/) | SVGZoomAndPan‑enumerationen definierar attributet zoomAndPan och tillhörande konstanter. |
