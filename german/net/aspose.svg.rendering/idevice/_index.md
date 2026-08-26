---
title: "IDevice‑Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Rendering.IDevice interface. Definiert Methoden und Eigenschaften, die benutzerdefiniertes Rendern von grafischen Elementen wie Pfaden, Text und Bildern unterstützen"
type: docs
weight: 4890
url: /de/net/aspose.svg.rendering/idevice/
---
## IDevice interface

Definiert Methoden und Eigenschaften, die benutzerdefiniertes Rendering von grafischen Elementen wie Pfaden, Text und Bildern unterstützen.

```csharp
public interface IDevice : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | Ermittelt den Grafik‑Kontext. |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | Ermittelt die Rendering‑Optionen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(*RectangleF*) | Fügt ein Rechteck zum aktuellen Pfad als vollständigen Unterpfad hinzu. |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Beginnt das Rendern des Dokuments. |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Beginnt das Rendern des Elements. |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(*SizeF*) | Beginnt das Rendern der neuen Seite. |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Modifiziert den aktuellen Clipping‑Pfad, indem er mit dem aktuellen Pfad geschnitten wird, wobei die FillRule zur Bestimmung des zu füllenden Bereichs verwendet wird. Diese Methode beendet den aktuellen Pfad. |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | Schließt den aktuellen Unterpfad, indem ein gerader Linienabschnitt vom aktuellen Punkt zum Startpunkt des Unterpfads hinzugefügt wird. Wenn der aktuelle Unterpfad bereits geschlossen ist, bewirkt „ClosePath“ nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Hinzufügen eines weiteren Segments zum aktuellen Pfad startet einen neuen Unterpfad, selbst wenn das neue Segment am Endpunkt beginnt, der durch die Methode „ClosePath“ erreicht wurde. |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | Fügt dem aktuellen Pfad eine kubische Bézier‑Kurve hinzu. Die Kurve erstreckt sich vom aktuellen Punkt zum Punkt pt3 und verwendet pt1 und pt2 als Bézier‑Steuerpunkte. Der neue aktuelle Punkt ist pt3. |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Zeichnet das angegebene Bild. |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | Beendet das Rendern des Dokuments. |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Beendet das Rendern des Elements. |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Füllt den gesamten von dem aktuellen Pfad umschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er die Innenbereiche aller Teilpfade zusammen. Diese Methode beendet den aktuellen Pfad. |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(*string, PointF*) | Füllt die angegebene Textzeichenfolge an der angegebenen Position. |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | Spült alle Daten in den Ausgabestream. |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(*PointF*) | Fügt ein gerades Liniensegment vom aktuellen Punkt zum Punkt (pt) hinzu. Der neue aktuelle Punkt ist pt. |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(*PointF*) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt zu den Koordinaten des Parameters pt verschoben wird, wobei ein verbindendes Liniensegment weggelassen wird. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad ebenfalls \"MoveTo\" war, überschreibt das neue \"MoveTo\" sie; es bleibt kein Rest der vorherigen \"MoveTo\"-Operation im Pfad erhalten. |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | Stellt den gesamten Grafik-Kontext auf seinen vorherigen Wert wieder her, indem er vom Stapel entfernt wird. |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | Schiebt eine Kopie des gesamten Grafik-Kontexts auf den Stapel. |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die gezeichnete Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallel verlaufenden Seiten. Jeder Teilpfad des Pfads wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Zeichnet die Kontur und füllt den aktuellen Pfad. Diese Methode beendet den aktuellen Pfad. |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(*string, PointF*) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position. |

### Siehe auch

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
