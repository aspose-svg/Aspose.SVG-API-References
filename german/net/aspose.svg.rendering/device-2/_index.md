---
title: "DeviceTGraphicContextTRenderingOptions Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions Klasse. Stellt die Basisklasse für die Implementierung bestimmter Rendering-Geräte dar"
type: docs
weight: 4820
url: /de/net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

Stellt die Basisklasse für die Implementierung bestimmter Rendering-Geräte dar.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Beschreibung |
| --- | --- |
| TGraphicContext | Grafikkontext, der die aktuellen Grafik-Steuerungsparameter enthält |
| TRenderingOptions | Renderoptionen |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | Ruft den Grafik-Kontext ab |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | Ermittelt die Rendering‑Optionen. |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | Ruft die Gerätekonfiguration ab. |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | Setzt und ruft den Ausgabestream ab. |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | Ruft das Stream-Provider-Objekt ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | Fügt ein Rechteck zum aktuellen Pfad als vollständigen Unterpfad hinzu. |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Beginnt das Rendern des Dokuments. |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Beginnt das Rendern des Knotens. |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | Beginnt das Rendern der neuen Seite. |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Modifiziert den aktuellen Clipping‑Pfad, indem er mit dem aktuellen Pfad geschnitten wird, wobei die FillRule zur Bestimmung des zu füllenden Bereichs verwendet wird. Diese Methode beendet den aktuellen Pfad. |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | Schließt den aktuellen Unterpfad, indem ein gerader Linienabschnitt vom aktuellen Punkt zum Startpunkt des Unterpfads hinzugefügt wird. Wenn der aktuelle Unterpfad bereits geschlossen ist, bewirkt „ClosePath“ nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Hinzufügen eines weiteren Segments zum aktuellen Pfad startet einen neuen Unterpfad, selbst wenn das neue Segment am Endpunkt beginnt, der durch die Methode „ClosePath“ erreicht wurde. |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | Fügt dem aktuellen Pfad eine kubische Bézier-Kurve hinzu. Die Kurve erstreckt sich vom aktuellen Punkt zum Punkt pt2 und verwendet pt1 und pt2 als Bézier-Steuerpunkte. Der neue aktuelle Punkt ist pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Zeichnet das angegebene Bild. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | Beendet das Rendern des Dokuments. |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Beendet das Rendern des Knotens. |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Füllt den gesamten von dem aktuellen Pfad umschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er die Innenbereiche aller Teilpfade zusammen. Diese Methode beendet den aktuellen Pfad. |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | Füllt die angegebene Textzeichenfolge an der angegebenen Position. |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | Spült alle Daten in den Ausgabestream. |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | Fügt ein gerades Liniensegment vom aktuellen Punkt zum Punkt (pt) hinzu. Der neue aktuelle Punkt ist pt. |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt zu den Koordinaten des Parameters pt verschoben wird, wobei ein verbindendes Liniensegment weggelassen wird. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad ebenfalls \"MoveTo\" war, überschreibt das neue \"MoveTo\" sie; es bleibt kein Rest der vorherigen \"MoveTo\"-Operation im Pfad erhalten. |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | Stellt den gesamten Grafik-Kontext auf seinen vorherigen Wert wieder her, indem er vom Stapel entfernt wird. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | Schiebt eine Kopie des gesamten Grafik-Kontexts auf den Stapel. |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die gezeichnete Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallel verlaufenden Seiten. Jeder Teilpfad des Pfads wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Zeichnet die Kontur und füllt den aktuellen Pfad. Diese Methode beendet den aktuellen Pfad. |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | Stellt ein Konfigurationsobjekt für Geräte dar. |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | Gibt die Arten von Strategien zum Schreiben von Seiten in Ausgabestream\streams an. |

### Siehe auch

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
