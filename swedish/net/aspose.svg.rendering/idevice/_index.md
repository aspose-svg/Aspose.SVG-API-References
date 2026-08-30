---
title: "IDevice Interface"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Rendering.IDevice interface. Definierar metoder och egenskaper som stödjer anpassad rendering av grafiska element som banor, text och bilder."
type: docs
weight: 4890
url: /sv/net/aspose.svg.rendering/idevice/
---
## IDevice interface

Definierar metoder och egenskaper som stödjer anpassad rendering av grafiska element som banor, text och bilder.

```csharp
public interface IDevice : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | Hämtar den grafiska kontexten. |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | Hämtar renderingsalternativ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(*RectangleF*) | Lägger till en rektangel till den aktuella banan som en komplett delbana. |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Påbörjar rendering av dokumentet. |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Påbörjar rendering av elementet. |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(*SizeF*) | Påbörjar rendering av den nya sidan. |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Modifierar den aktuella klippningsbanan genom att skära den med den aktuella banan, med hjälp av FillRule för att bestämma området som ska fyllas. Denna metod avslutar den aktuella banan. |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | Stänger den aktuella delbanan genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för delbanan. Om den aktuella delbanan redan är stängd gör "ClosePath" inget. Denna operator avslutar den aktuella delbanan. Att lägga till ett annat segment till den aktuella banan startar en ny delbana, även om det nya segmentet börjar vid slutpunkten som nås av "ClosePath"-metoden. |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | Lägger till en kubisk Bézier-kurva till den aktuella banan. Kurvan sträcker sig från den aktuella punkten till punkten pt3, med pt1 och pt2 som Bézier-kontrollpunkter. Den nya aktuella punkten är pt3. |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Ritar den angivna bilden. |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | Avslutar rendering av dokumentet. |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Avslutar rendering av elementet. |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | Avslutar rendering av den aktuella sidan. |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Fyller hela området som omsluts av den aktuella banan. Om banan består av flera separata delbanor fyller den insidan av alla delbanor, betraktade tillsammans. Denna metod avslutar den aktuella banan. |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(*string, PointF*) | Fyller den angivna textsträngen på den angivna platsen. |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | Spolar alla data till utdataflödet. |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(*PointF*) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya aktuella punkten är pt. |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(*PointF*) | Påbörjar en ny underbana genom att flytta den aktuella punkten till koordinaterna för parametern pt, utan att lägga till något anslutningslinjesegment. Om den föregående bankonstruktionsmetoden i den aktuella banan också var \"MoveTo\", så åsidosätter den nya \"MoveTo\" den; inget spår av den föregående \"MoveTo\"-operationen finns kvar i banan. |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | Pukar en kopia av hela grafikkontexten på stacken. |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | Ritar en linje längs den aktuella banan. Den ritade linjen följer varje rakt eller kurvat segment i banan, centrerad på segmentet med sidor parallella med det. Varje av banans underbanor behandlas separat. Denna metod avslutar den aktuella banan. |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Ritar och fyller den aktuella banan. Denna metod avslutar den aktuella banan. |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(*string, PointF*) | Ritar den angivna textsträngen på den angivna platsen. |

### Se även

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
