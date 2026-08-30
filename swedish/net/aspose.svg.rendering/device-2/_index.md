---
title: "DeviceTGraphicContextTRenderingOptions klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions klass. Representerar basklass för implementering av särskilda renderingsenheter"
type: docs
weight: 4820
url: /sv/net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

Representerar basklass för implementering av specifika renderingsenheter.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Beskrivning |
| --- | --- |
| TGraphicContext | Grafisk kontext som innehåller aktuella grafikstyrningsparametrar |
| TRenderingOptions | Renderingsalternativ |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | Hämtar den grafiska kontexten |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | Hämtar renderingsalternativ. |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | Hämtar enhetskonfigurationen. |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | Ställer in och hämtar utdataflödet. |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | Hämtar strömleverantörsobjektet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | Lägger till en rektangel till den aktuella banan som en komplett delbana. |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Påbörjar rendering av dokumentet. |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Påbörjar rendering av noden. |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | Påbörjar rendering av den nya sidan. |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Modifierar den aktuella klippningsbanan genom att skära den med den aktuella banan, med hjälp av FillRule för att bestämma området som ska fyllas. Denna metod avslutar den aktuella banan. |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | Stänger den aktuella delbanan genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för delbanan. Om den aktuella delbanan redan är stängd gör "ClosePath" inget. Denna operator avslutar den aktuella delbanan. Att lägga till ett annat segment till den aktuella banan startar en ny delbana, även om det nya segmentet börjar vid slutpunkten som nås av "ClosePath"-metoden. |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | Lägger till en kubisk Bézier-kurva till den aktuella vägen. Kurvan sträcker sig från den aktuella punkten till punkten pt2, med pt1 och pt2 som Bézier-kontrollpunkter. Den nya aktuella punkten är pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Ritar den angivna bilden. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | Avslutar rendering av dokumentet. |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Avslutar rendering av noden. |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | Avslutar rendering av den aktuella sidan. |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Fyller hela området som omsluts av den aktuella banan. Om banan består av flera separata delbanor fyller den insidan av alla delbanor, betraktade tillsammans. Denna metod avslutar den aktuella banan. |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | Fyller den angivna textsträngen på den angivna platsen. |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | Spolar alla data till utdataflödet. |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya aktuella punkten är pt. |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | Påbörjar en ny underbana genom att flytta den aktuella punkten till koordinaterna för parametern pt, utan att lägga till något anslutningslinjesegment. Om den föregående bankonstruktionsmetoden i den aktuella banan också var \"MoveTo\", så åsidosätter den nya \"MoveTo\" den; inget spår av den föregående \"MoveTo\"-operationen finns kvar i banan. |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | Pukar en kopia av hela grafikkontexten på stacken. |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | Ritar en linje längs den aktuella banan. Den ritade linjen följer varje rakt eller kurvat segment i banan, centrerad på segmentet med sidor parallella med det. Varje av banans underbanor behandlas separat. Denna metod avslutar den aktuella banan. |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Ritar och fyller den aktuella banan. Denna metod avslutar den aktuella banan. |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | Ritar den angivna textsträngen på den angivna platsen. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | Representerar konfigurationsobjekt för enheter. |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | Anger typer av strategier för att skriva sidor till utdataflöde\strömmar. |

### Se även

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
