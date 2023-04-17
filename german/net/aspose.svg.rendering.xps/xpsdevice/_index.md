---
title: Class XpsDevice
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Rendering.Xps.XpsDevice klas. Stellt das Rendern in ein XPSDokument dar.
type: docs
weight: 3050
url: /de/net/aspose.svg.rendering.xps/xpsdevice/
---
## XpsDevice class

Stellt das Rendern in ein XPS-Dokument dar.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Initialisiert eine neue Instanz von`XpsDevice` Klasse. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Initialisiert eine neue Instanz von`XpsDevice` Klasse. |
| [XpsDevice](xpsdevice/#constructor_5)(string) | Initialisiert eine neue Instanz von`XpsDevice` Klasse. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initialisiert eine neue Instanz von`XpsDevice` Klasse nach Rendering-Optionen und Stream-Provider. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Initialisiert eine neue Instanz von`XpsDevice` Klasse nach Rendering-Optionen und Ausgabestream. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, string) | Initialisiert eine neue Instanz von`XpsDevice` Klasse nach Rendering-Optionen und Name der Ausgabedatei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [AddRect](../../aspose.svg.rendering.xps/xpsdevice/addrect/)(RectangleF) | Hängt ein Rechteck als vollständigen Teilpfad an den aktuellen Pfad an. |
| override [BeginDocument](../../aspose.svg.rendering.xps/xpsdevice/begindocument/)(Document) | Beginnt mit der Wiedergabe des Dokuments. |
| override [BeginElement](../../aspose.svg.rendering.xps/xpsdevice/beginelement/)(Element, RectangleF) | Beginnt mit dem Rendern des Elements. |
| override [BeginPage](../../aspose.svg.rendering.xps/xpsdevice/beginpage/)(SizeF) | Beginnt mit dem Rendern der neuen Seite. |
| override [Clip](../../aspose.svg.rendering.xps/xpsdevice/clip/)(FillMode) | Ändert den aktuellen Beschneidungspfad, indem er ihn mit dem aktuellen Pfad schneidet, wobei die FillMode-Regel verwendet wird, um den zu füllenden Bereich zu bestimmen. Diese Methode beendet den aktuellen Pfad. |
| override [ClosePath](../../aspose.svg.rendering.xps/xpsdevice/closepath/)() | Schließt den aktuellen Unterpfad durch Anhängen eines geraden Liniensegments vom aktuellen Punkt an den Startpunkt des Unterpfads. Wenn der aktuelle Unterpfad bereits geschlossen ist, tut "ClosePath" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Anhängen eines weiteren Segments an den aktuellen Pfad beginnt einen neuen Unterpfad, , selbst wenn das neue Segment an dem Endpunkt beginnt, der von der „ClosePath“-Methode erreicht wird. |
| override [CubicBezierTo](../../aspose.svg.rendering.xps/xpsdevice/cubicbezierto/)(PointF, PointF, PointF) | Hängt eine kubische Bézier-Kurve an den aktuellen Pfad an. Die Kurve erstreckt sich vom aktuellen Punkt bis zum Punkt pt2, , wobei pt1 und pt2 als Bézier-Kontrollpunkte verwendet werden. Der neue aktuelle Punkt ist pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.svg.rendering.xps/xpsdevice/drawimage/)(byte[], ImageType, RectangleF) | Zeichnet das angegebene Bild. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.svg.rendering.xps/xpsdevice/endelement/)(Element) | Beendet das Rendern des Elements. |
| override [EndPage](../../aspose.svg.rendering.xps/xpsdevice/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| override [Fill](../../aspose.svg.rendering.xps/xpsdevice/fill/)(FillMode) | Füllt den gesamten vom aktuellen Pfad eingeschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er das Innere aller Teilpfade aus, zusammen betrachtet. Diese Methode beendet den aktuellen Pfad. |
| override [FillText](../../aspose.svg.rendering.xps/xpsdevice/filltext/)(string, PointF) | Füllt die angegebene Textzeichenfolge an der angegebenen Stelle aus. |
| override [Flush](../../aspose.svg.rendering.xps/xpsdevice/flush/)() | Flusht alle Daten in den Ausgabestream. |
| override [LineTo](../../aspose.svg.rendering.xps/xpsdevice/lineto/)(PointF) | Hängt ein gerades Liniensegment vom aktuellen Punkt an den Punkt (pt) an. Der neue aktuelle Punkt ist pt. |
| override [MoveTo](../../aspose.svg.rendering.xps/xpsdevice/moveto/)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt auf die Koordinaten des Parameters pt verschoben wird, wobei alle Verbindungsliniensegmente weggelassen werden. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad auch "MoveTo" war, überschreibt das neue "MoveTo" sie; keine Spur der vorherigen "MoveTo"-Operation bleibt im Pfad. |
| override [RestoreGraphicContext](../../aspose.svg.rendering.xps/xpsdevice/restoregraphiccontext/)() | Stellt den gesamten Grafikkontext auf seinen früheren Wert wieder her, indem er vom Stapel entfernt wird. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() |  |
| override [Stroke](../../aspose.svg.rendering.xps/xpsdevice/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die strichlierte Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallelen Seiten dazu. Jeder der Teilpfade des Pfades wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| override [StrokeAndFill](../../aspose.svg.rendering.xps/xpsdevice/strokeandfill/)(FillMode) | Striche und aktuellen Pfad füllen. Diese Methode beendet aktuellen Pfad. |
| override [StrokeText](../../aspose.svg.rendering.xps/xpsdevice/stroketext/)(string, PointF) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext/) | Enthält aktuelle Grafiksteuerungsparameter für das XpsDevice. Diese Parameter definieren den globalen Rahmen, in dem die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* namensraum [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps/)
* Montage [Aspose.SVG](../../)


