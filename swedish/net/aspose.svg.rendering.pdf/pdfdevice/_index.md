---
title: "PdfDevice-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Rendering.Pdf.PdfDevice-klass. Representerar rendering till ett pdf-dokument"
type: docs
weight: 5020
url: /sv/net/aspose.svg.rendering.pdf/pdfdevice/
---
## PdfDevice class

Representerar rendering till ett PDF-dokument.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(*[ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | Initierar en ny instans av klassen `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(*Stream*) | Initierar en ny instans av klassen `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(*string*) | Initierar en ny instans av klassen `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(*[PdfRenderingOptions](../pdfrenderingoptions/), [ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | Initierar en ny instans av klassen `PdfDevice` med renderingsalternativ och strömleverantör. |
| [PdfDevice](pdfdevice/#constructor_2)(*[PdfRenderingOptions](../pdfrenderingoptions/), Stream*) | Initierar en ny instans av klassen `PdfDevice` med renderingsalternativ och utdataström. |
| [PdfDevice](pdfdevice/#constructor_3)(*[PdfRenderingOptions](../pdfrenderingoptions/), string*) | Initierar en ny instans av klassen `PdfDevice` med renderingsalternativ och utdatafilnamn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } |  |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } |  |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } |  |

## Metoder

| Namn | Beskrivning |
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

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [PdfGraphicContext](../../aspose.svg.rendering.pdf/pdfdevice.pdfgraphiccontext) | Innehåller aktuella grafikstyrningsparametrar för PdfDevice. Dessa parametrar definierar den globala ramen inom vilken grafikoperatorerna körs. |

### Se även

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* namespace [Aspose.Svg.Rendering.Pdf](../../aspose.svg.rendering.pdf/)
* assembly [Aspose.SVG](../../)
