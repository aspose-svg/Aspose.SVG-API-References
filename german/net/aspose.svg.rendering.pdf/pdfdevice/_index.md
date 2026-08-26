---
title: "PdfDevice-Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Rendering.Pdf.PdfDevice-Klasse. Stellt das Rendering in ein PDF-Dokument dar."
type: docs
weight: 5020
url: /de/net/aspose.svg.rendering.pdf/pdfdevice/
---
## PdfDevice class

Stellt das Rendern in ein PDF‑Dokument dar.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(*[ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | Initialisiert eine neue Instanz der Klasse `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(*Stream*) | Initialisiert eine neue Instanz der Klasse `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(*string*) | Initialisiert eine neue Instanz der Klasse `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(*[PdfRenderingOptions](../pdfrenderingoptions/), [ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | Initialisiert eine neue Instanz der Klasse `PdfDevice` mittels Rendering-Optionen und Stream-Anbieter. |
| [PdfDevice](pdfdevice/#constructor_2)(*[PdfRenderingOptions](../pdfrenderingoptions/), Stream*) | Initialisiert eine neue Instanz der Klasse `PdfDevice` mittels Rendering-Optionen und Ausgabestream. |
| [PdfDevice](pdfdevice/#constructor_3)(*[PdfRenderingOptions](../pdfrenderingoptions/), string*) | Initialisiert eine neue Instanz der Klasse `PdfDevice` mittels Rendering-Optionen und Ausgabedateinamen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } |  |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } |  |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) |  |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) |  |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) |  |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) |  |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() |  |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) |  |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() |  |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) |  |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() |  |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) |  |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() |  |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) |  |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) |  |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() |  |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) |  |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) |  |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() |  |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() |  |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() |  |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) |  |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) |  |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [PdfGraphicContext](../../aspose.svg.rendering.pdf/pdfdevice.pdfgraphiccontext) | Hält aktuelle Grafiksteuerungsparameter für das PdfDevice. Diese Parameter definieren das globale Rahmenwerk, in dem die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* namespace [Aspose.Svg.Rendering.Pdf](../../aspose.svg.rendering.pdf/)
* assembly [Aspose.SVG](../../)
