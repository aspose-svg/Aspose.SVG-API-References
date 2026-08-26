---
title: "PdfDevice Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Rendering.Pdf.PdfDevice κλάση. Αντιπροσωπεύει την απόδοση σε ένα έγγραφο pdf"
type: docs
weight: 5020
url: /el/net/aspose.svg.rendering.pdf/pdfdevice/
---
## PdfDevice class

Αναπαριστά την απόδοση σε ένα έγγραφο pdf.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(*[ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(*Stream*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(*string*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(*[PdfRenderingOptions](../pdfrenderingoptions/), [ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `PdfDevice` με επιλογές απόδοσης και πάροχο ροής. |
| [PdfDevice](pdfdevice/#constructor_2)(*[PdfRenderingOptions](../pdfrenderingoptions/), Stream*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `PdfDevice` με επιλογές απόδοσης και ροή εξόδου. |
| [PdfDevice](pdfdevice/#constructor_3)(*[PdfRenderingOptions](../pdfrenderingoptions/), string*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `PdfDevice` με επιλογές απόδοσης και όνομα αρχείου εξόδου. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } |  |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } |  |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } |  |

## Μέθοδοι

| Όνομα | Περιγραφή |
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

## Άλλα Μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| class [PdfGraphicContext](../../aspose.svg.rendering.pdf/pdfdevice.pdfgraphiccontext) | Διατηρεί τις τρέχουσες παραμέτρους ελέγχου γραφικών για το PdfDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών. |

### Δείτε επίσης

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* namespace [Aspose.Svg.Rendering.Pdf](../../aspose.svg.rendering.pdf/)
* assembly [Aspose.SVG](../../)
