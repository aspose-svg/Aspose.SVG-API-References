---
title: Interface IDevice
second_title: Aspose.SVG för .NET API Referens
description: Aspose.Svg.Rendering.IDevice gränssnitt. Definierar metoder och egenskaper som stöder anpassad rendering av de grafiska elementen som sökvägar text och bilder.
type: docs
weight: 2810
url: /sv/net/aspose.svg.rendering/idevice/
---
## IDevice interface

Definierar metoder och egenskaper som stöder anpassad rendering av de grafiska elementen som sökvägar, text och bilder.

```csharp
public interface IDevice : IDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | Får det grafiska sammanhanget. |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | Får renderingsalternativ. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(RectangleF) | Lägger till en rektangel till den aktuella sökvägen som en komplett undersökväg. |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(Document) | Börjar renderingen av dokumentet. |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(Element, RectangleF) | Börjar rendering av elementet. |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(SizeF) | Börjar renderingen av den nya sidan. |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(FillMode) | Modifierar den aktuella urklippsbanan genom att skära den med den aktuella sökvägen, med hjälp av FillMode-regeln för att bestämma regionen som ska fyllas. Den här metoden avslutar aktuell väg. |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | Stänger den aktuella delvägen genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för delvägen. Om den aktuella undersökvägen redan är stängd, gör "ClosePath" ingenting. Denna operatör avslutar den aktuella undersökvägen. Genom att lägga till ett annat segment till den aktuella sökvägen börjar en ny undersökväg, även om det nya segmentet börjar vid den slutpunkt som nås med "ClosePath"-metoden. |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Lägger till en kubisk Bézier-kurva till den aktuella sökvägen. Kurvan sträcker sig från den aktuella punkten till punkten pt3, med pt1 och pt2 som Bézier-kontrollpunkter. Den nya aktuella punkten är pt3. |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | Ritar den angivna bilden. |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | Avslutar renderingen av dokumentet. |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(Element) | Avslutar renderingen av elementet. |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | Avslutar renderingen av den aktuella sidan. |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(FillMode) | Fyller hela området som omges av den aktuella sökvägen. Om sökvägen består av flera frånkopplade undersökvägar, fyller den insidan av alla undersökvägar, betraktat tillsammans. Den här metoden avslutar aktuell väg. |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(string, PointF) | Fyller den angivna textsträngen på den angivna platsen. |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | Rensar all data till utdataström. |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(PointF) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya nuvarande punkten är pt. |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(PointF) | Börjar en ny undersökväg genom att flytta den aktuella punkten till koordinaterna för parametern pt, och utelämnar alla anslutande linjesegment. Om den tidigare vägkonstruktionsmetoden i den aktuella sökvägen också var "MoveTo", åsidosätter den nya "MoveTo" den; ingen rest av den tidigare "MoveTo"-operationen finns kvar i sökvägen. |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | Skickar en kopia av hela grafikkontexten till stacken. |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | Stryker en linje längs den aktuella banan. Den streckade linjen följer varje rakt eller krökt segment i banan, centrerat på segmentet med sidor parallella med det. Var och en av sökvägens undervägar behandlas separat. Den här metoden avslutar aktuell väg. |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(FillMode) | Stryker och fyller strömvägen. Denna metod avslutar strömvägen. |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(string, PointF) | Stryker den angivna textsträngen på den angivna platsen. |

### Se även

* namnutrymme [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* hopsättning [Aspose.SVG](../../)


