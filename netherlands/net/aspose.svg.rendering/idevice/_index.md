---
title: "IDevice Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Rendering.IDevice interface. Definieert methoden en eigenschappen die aangepaste weergave van grafische elementen zoals paden, tekst en afbeeldingen ondersteunen."
type: docs
weight: 4890
url: /nl/net/aspose.svg.rendering/idevice/
---
## IDevice interface

Definieert methoden en eigenschappen die aangepaste rendering van grafische elementen zoals paden, tekst en afbeeldingen ondersteunen.

```csharp
public interface IDevice : IDisposable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | Haalt de grafische context op. |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | Haalt renderopties op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(*RectangleF*) | Voegt een rechthoek toe aan het huidige pad als een volledige subpad. |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Begint met renderen van het document. |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Begint met renderen van het element. |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(*SizeF*) | Begint met renderen van de nieuwe pagina. |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Wijzigt het huidige knippad door het te kruisen met het huidige pad, waarbij de FillRule wordt gebruikt om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | Sluit het huidige subpad door een rechte lijnsegment toe te voegen van het huidige punt naar het startpunt van het subpad. Als het huidige subpad al gesloten is, doet \"ClosePath\" niets. Deze operator beëindigt het huidige subpad. Het toevoegen van een ander segment aan het huidige pad start een nieuw subpad, zelfs als het nieuwe segment begint bij het eindpunt dat door de \"ClosePath\"‑methode is bereikt. |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | Voegt een kubieke Bézier‑curve toe aan het huidige pad. De curve loopt van het huidige punt naar punt pt3, waarbij pt1 en pt2 worden gebruikt als Bézier‑controlepunten. Het nieuwe huidige punt is pt3. |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Tekent de opgegeven afbeelding. |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | Beëindigt het renderen van het document. |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Beëindigt het renderen van het element. |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Vult het gehele gebied dat door het huidige pad wordt omsloten. Als het pad bestaat uit meerdere losse subpaden, vult het de binnenkant van alle subpaden samen. Deze methode beëindigt het huidige pad. |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(*string, PointF*) | Vult de opgegeven tekenreeks op de opgegeven locatie. |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | Leegt alle gegevens naar de uitvoerstroom. |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(*PointF*) | Voegt een rechte lijnsegment toe vanaf het huidige punt naar het punt (pt). Het nieuwe huidige punt is pt. |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(*PointF*) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, zonder een verbindingslijnsegment. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; er blijft geen spoor van de vorige "MoveTo"-bewerking in het pad. |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze van de stack te halen. |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | Zet een kopie van de volledige grafische context op de stack. |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | Tekent een lijn langs het huidige pad. De getekende lijn volgt elk rechte of gebogen segment in het pad, gecentreerd op het segment met zijden die er evenwijdig aan zijn. Elk subpad van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Tekent en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(*string, PointF*) | Tekent de opgegeven tekenreeks op de opgegeven locatie. |

### Zie ook

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
