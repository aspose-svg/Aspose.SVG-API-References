---
title: DeviceTGraphicContextTRenderingOptions Class
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions class. Represents base class for implementation particular rendering devices
type: docs
weight: 4830
url: /net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

Represents base class for implementation particular rendering devices.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Description |
| --- | --- |
| TGraphicContext | Graphic context that holds current graphics control parameters |
| TRenderingOptions | Rendering options |

## Properties

| Name | Description |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | Gets the graphic context |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | Gets rendering options. |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | Gets device configuration. |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | Sets and gets the output stream. |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | Gets the stream provider object. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | Appends a rectangle to the current path as a complete subpath. |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Begins rendering of the document. |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Begins rendering of the node. |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | Begins rendering of the new page. |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Modifies the current clipping path by intersecting it with the current path, using the FillRule to determine the region to fill. This method terminates current path. |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Draws the specified image. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | Ends rendering of the document. |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Ends rendering of the node. |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | Ends rendering of the current page. |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | Fills the specified text string at the specified location. |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | Flushes all data to output stream. |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | Restores the entire graphics context to its former value by popping it from the stack. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | Pushes a copy of the entire graphics context onto the stack. |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Strokes and fill current path. This method terminates current path. |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | Strokes the specified text string at the specified location. |

## Other Members

| Name | Description |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | Represents configuration object for devices. |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | Specifies types of strategies for writing pages into output stream\streams. |

### See Also

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
