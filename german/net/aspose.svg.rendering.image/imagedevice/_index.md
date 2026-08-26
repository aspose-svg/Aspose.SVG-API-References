---
title: "ImageDevice Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Rendering.Image.ImageDevice Klasse. Stellt das Rendern in Rasterformate jpeg png bmp gif tiff dar."
type: docs
weight: 4910
url: /de/net/aspose.svg.rendering.image/imagedevice/
---
## ImageDevice class

Stellt das Rendern in Rasterformate dar: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(*[ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | Initialisiert eine neue Instanz der `ImageDevice` Klasse. |
| [ImageDevice](imagedevice/#constructor_4)(*Stream*) | Initialisiert eine neue Instanz der `ImageDevice` Klasse. |
| [ImageDevice](imagedevice/#constructor_5)(*string*) | Initialisiert eine neue Instanz der `ImageDevice` Klasse. |
| [ImageDevice](imagedevice/#constructor_1)(*[ImageRenderingOptions](../imagerenderingoptions/), [ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | Initialisiert eine neue Instanz der `ImageDevice` Klasse mittels Rendering-Optionen und Stream‑Provider. |
| [ImageDevice](imagedevice/#constructor_2)(*[ImageRenderingOptions](../imagerenderingoptions/), Stream*) | Initialisiert eine neue Instanz der `ImageDevice` Klasse mittels Rendering-Optionen und Ausgabestream. |
| [ImageDevice](imagedevice/#constructor_3)(*[ImageRenderingOptions](../imagerenderingoptions/), string*) | Initialisiert eine neue Instanz der `ImageDevice` Klasse mittels Rendering-Optionen und Ausgabedateinamen. |

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
| class [ImageGraphicContext](../../aspose.svg.rendering.image/imagedevice.imagegraphiccontext) | Enthält aktuelle Grafiksteuerungsparameter für die `ImageDevice`. Diese Parameter definieren das globale Rahmenwerk, in dem die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
