---
title: "DeviceTGraphicContextTRenderingOptions Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions klasse. Vertegenwoordigt de basisklasse voor de implementatie van specifieke renderapparaten"
type: docs
weight: 4820
url: /nl/net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

Stelt de basisklasse voor de implementatie van specifieke renderapparaten voor.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Beschrijving |
| --- | --- |
| TGraphicContext | Grafische context die de huidige grafische controleparameters bevat |
| TRenderingOptions | Renderopties |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | Haalt de grafische context op |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | Haalt renderopties op. |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | Haalt apparaatconfiguratie op. |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | Stelt de uitvoerstream in en haalt deze op. |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | Haalt het streamproviderobject op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | Voegt een rechthoek toe aan het huidige pad als een volledige subpad. |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Begint met renderen van het document. |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Begint met het renderen van het knooppunt. |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | Begint met renderen van de nieuwe pagina. |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Wijzigt het huidige knippad door het te kruisen met het huidige pad, waarbij de FillRule wordt gebruikt om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | Sluit het huidige subpad door een rechte lijnsegment toe te voegen van het huidige punt naar het startpunt van het subpad. Als het huidige subpad al gesloten is, doet \"ClosePath\" niets. Deze operator beëindigt het huidige subpad. Het toevoegen van een ander segment aan het huidige pad start een nieuw subpad, zelfs als het nieuwe segment begint bij het eindpunt dat door de \"ClosePath\"‑methode is bereikt. |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve loopt van het huidige punt naar het punt pt2, met pt1 en pt2 als Bézier-controlepunten. Het nieuwe huidige punt is pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Tekent de opgegeven afbeelding. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | Beëindigt het renderen van het document. |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Beëindigt het renderen van het knooppunt. |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Vult het gehele gebied dat door het huidige pad wordt omsloten. Als het pad bestaat uit meerdere losse subpaden, vult het de binnenkant van alle subpaden samen. Deze methode beëindigt het huidige pad. |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | Vult de opgegeven tekenreeks op de opgegeven locatie. |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | Leegt alle gegevens naar de uitvoerstroom. |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | Voegt een rechte lijnsegment toe vanaf het huidige punt naar het punt (pt). Het nieuwe huidige punt is pt. |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, zonder een verbindingslijnsegment. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; er blijft geen spoor van de vorige "MoveTo"-bewerking in het pad. |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze van de stack te halen. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | Zet een kopie van de volledige grafische context op de stack. |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | Tekent een lijn langs het huidige pad. De getekende lijn volgt elk rechte of gebogen segment in het pad, gecentreerd op het segment met zijden die er evenwijdig aan zijn. Elk subpad van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Tekent en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | Tekent de opgegeven tekenreeks op de opgegeven locatie. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | Vertegenwoordigt configuratieobject voor apparaten. |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | Specificeert typen strategieën voor het schrijven van pagina's naar uitvoerstroom\streams. |

### Zie ook

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
