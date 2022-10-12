---
title: XpsDevice
second_title: Aspose.SVG för .NET API Referens
description: Representerar rendering till ett XPSdokument.
type: docs
weight: 3000
url: /sv/net/aspose.svg.rendering.xps/xpsdevice/
---
## XpsDevice class

Representerar rendering till ett XPS-dokument.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XpsDevice](xpsdevice#constructor)(ICreateStreamProvider) | Initierar en ny instans av[`XpsDevice`](../xpsdevice) class. |
| [XpsDevice](xpsdevice#constructor_4)(Stream) | Initierar en ny instans av[`XpsDevice`](../xpsdevice) class. |
| [XpsDevice](xpsdevice#constructor_5)(string) | Initierar en ny instans av[`XpsDevice`](../xpsdevice) class. |
| [XpsDevice](xpsdevice#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initierar en ny instans av[`XpsDevice`](../xpsdevice) klass genom renderingsalternativ och strömleverantör. |
| [XpsDevice](xpsdevice#constructor_2)(XpsRenderingOptions, Stream) | Initierar en ny instans av[`XpsDevice`](../xpsdevice) klass genom att rendera alternativ och utdataström. |
| [XpsDevice](xpsdevice#constructor_3)(XpsRenderingOptions, string) | Initierar en ny instans av[`XpsDevice`](../xpsdevice) klass genom att rendera alternativ och utdatafilnamn. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.svg.rendering/device`2/options) { get; } |  |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [AddRect](../../aspose.svg.rendering.xps/xpsdevice/addrect)(RectangleF) | Lägger till en rektangel till den aktuella sökvägen som en komplett undersökväg. |
| override [BeginDocument](../../aspose.svg.rendering.xps/xpsdevice/begindocument)(Document) | Börjar renderingen av dokumentet. |
| override [BeginElement](../../aspose.svg.rendering.xps/xpsdevice/beginelement)(Element, RectangleF) | Börjar rendering av elementet. |
| override [BeginPage](../../aspose.svg.rendering.xps/xpsdevice/beginpage)(SizeF) | Börjar renderingen av den nya sidan. |
| override [Clip](../../aspose.svg.rendering.xps/xpsdevice/clip)(FillMode) | Modifierar den aktuella urklippsbanan genom att skära den med den aktuella sökvägen, med hjälp av FillMode-regeln för att bestämma regionen som ska fyllas. Den här metoden avslutar aktuell väg. |
| override [ClosePath](../../aspose.svg.rendering.xps/xpsdevice/closepath)() | Stänger den aktuella delvägen genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för delvägen. Om den aktuella undersökvägen redan är stängd, gör "ClosePath" ingenting. Denna operatör avslutar den aktuella undersökvägen. Genom att lägga till ett annat segment till den aktuella sökvägen börjar en ny undersökväg, även om det nya segmentet börjar vid den slutpunkt som nås med "ClosePath"-metoden. |
| override [CubicBezierTo](../../aspose.svg.rendering.xps/xpsdevice/cubicbezierto)(PointF, PointF, PointF) | Lägger till en kubisk Bézier-kurva till den aktuella sökvägen. Kurvan sträcker sig från den aktuella punkten till punkten pt2, med pt1 och pt2 som Bézier-kontrollpunkter. Den nya aktuella punkten är pt3. |
| [Dispose](../../aspose.svg.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.svg.rendering.xps/xpsdevice/drawimage)(byte[], ImageType, RectangleF) | Ritar den angivna bilden. |
| virtual [EndDocument](../../aspose.svg.rendering/device`2/enddocument)() |  |
| override [EndElement](../../aspose.svg.rendering.xps/xpsdevice/endelement)(Element) | Avslutar renderingen av elementet. |
| override [EndPage](../../aspose.svg.rendering.xps/xpsdevice/endpage)() | Avslutar renderingen av den aktuella sidan. |
| override [Fill](../../aspose.svg.rendering.xps/xpsdevice/fill)(FillMode) | Fyller hela området som omges av den aktuella sökvägen. Om sökvägen består av flera frånkopplade undersökvägar, fyller den insidan av alla undersökvägar, betraktat tillsammans. Den här metoden avslutar aktuell väg. |
| override [FillText](../../aspose.svg.rendering.xps/xpsdevice/filltext)(string, PointF) | Fyller den angivna textsträngen på den angivna platsen. |
| override [Flush](../../aspose.svg.rendering.xps/xpsdevice/flush)() | Rensar all data till utdataström. |
| override [LineTo](../../aspose.svg.rendering.xps/xpsdevice/lineto)(PointF) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya nuvarande punkten är pt. |
| override [MoveTo](../../aspose.svg.rendering.xps/xpsdevice/moveto)(PointF) | Börjar en ny undersökväg genom att flytta den aktuella punkten till koordinaterna för parametern pt, och utelämnar alla anslutande linjesegment. Om den tidigare vägkonstruktionsmetoden i den aktuella sökvägen också var "MoveTo", åsidosätter den nya "MoveTo" den; ingen rest av den tidigare "MoveTo"-operationen finns kvar i sökvägen. |
| override [RestoreGraphicContext](../../aspose.svg.rendering.xps/xpsdevice/restoregraphiccontext)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device`2/savegraphiccontext)() |  |
| override [Stroke](../../aspose.svg.rendering.xps/xpsdevice/stroke)() | Stryker en linje längs den aktuella banan. Den streckade linjen följer varje rakt eller krökt segment i banan, centrerat på segmentet med sidor parallella med det. Var och en av sökvägens undervägar behandlas separat. Den här metoden avslutar aktuell väg. |
| override [StrokeAndFill](../../aspose.svg.rendering.xps/xpsdevice/strokeandfill)(FillMode) | Stryker och fyller strömvägen. Denna metod avslutar strömvägen. |
| override [StrokeText](../../aspose.svg.rendering.xps/xpsdevice/stroketext)(string, PointF) | Stryker den angivna textsträngen på den angivna platsen. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext) | Innehåller aktuella grafikkontrollparametrar för XpsDevice. Dessa parametrar definierar det globala ramverket inom vilket grafikoperatörerna kör. |

### Se även

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext)
* class [XpsRenderingOptions](../xpsrenderingoptions)
* namnutrymme [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps)
* hopsättning [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
