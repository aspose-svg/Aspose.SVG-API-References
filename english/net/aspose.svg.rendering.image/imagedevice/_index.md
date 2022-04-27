---
title: ImageDevice
second_title: Aspose.SVG for .NET API Reference
description: 
type: docs
weight: 2760
url: /net/aspose.svg.rendering.image/imagedevice/
---
## ImageDevice class

Represents rendering to raster formats: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageDevice](imagedevice)(ICreateStreamProvider) | Initializes a new instance of the [`ImageDevice`](../imagedevice) class. |
| [ImageDevice](imagedevice)(Stream) | Initializes a new instance of the [`ImageDevice`](../imagedevice) class. |
| [ImageDevice](imagedevice)(string) | Initializes a new instance of the [`ImageDevice`](../imagedevice) class. |
| [ImageDevice](imagedevice)(ImageRenderingOptions, ICreateStreamProvider) | Initializes a new instance of the [`ImageDevice`](../imagedevice) class by rendering options and stream provider. |
| [ImageDevice](imagedevice)(ImageRenderingOptions, Stream) | Initializes a new instance of the [`ImageDevice`](../imagedevice) class by rendering options and output stream. |
| [ImageDevice](imagedevice)(ImageRenderingOptions, string) | Initializes a new instance of the [`ImageDevice`](../imagedevice) class by rendering options and output file name. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Graphics](graphics) { get; } | Gets the instance of Graphics. |

## Methods

| Name | Description |
| --- | --- |
| override [AddRect](addrect)(RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| override [BeginDocument](begindocument)(Document) | Begins rendering of the document. |
| override [BeginElement](beginelement)(Element, RectangleF) | Begins rendering of the element. |
| override [BeginPage](beginpage)(SizeF) | Begins rendering of the new page. |
| override [Clip](clip)(FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. This method terminates current path. |
| override [ClosePath](closepath)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| override [CubicBezierTo](cubicbezierto)(PointF, PointF, PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| override [DrawImage](drawimage)(byte[], ImageType, RectangleF) | Draws the specified image. |
| override [EndDocument](enddocument)() | Ends rendering of the document. |
| override [EndElement](endelement)(Element) | Ends rendering of the element. |
| override [EndPage](endpage)() | Ends rendering of the current page. |
| override [Fill](fill)(FillMode) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| override [FillText](filltext)(string, PointF) | Fills the specified text string at the specified location. |
| override [Flush](flush)() | Flushes all data to output stream. |
| override [LineTo](lineto)(PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| override [MoveTo](moveto)(PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| override [RestoreGraphicContext](restoregraphiccontext)() | Restores the entire graphics context to its former value by popping it from the stack. |
| override [SaveGraphicContext](savegraphiccontext)() | Pushes a copy of the entire graphics context onto the stack. |
| override [Stroke](stroke)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| override [StrokeAndFill](strokeandfill)(FillMode) | Strokes and fill current path. This method terminates current path. |
| override [StrokeText](stroketext)(string, PointF) | Strokes the specified text string at the specified location. |

## Other Members

| Name | Description |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext) | Holds current graphics control parameters for the [`ImageDevice`](../imagedevice). These parameters define the global framework within which the graphics operators execute. |

### See Also

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2)
* class [ImageRenderingOptions](../imagerenderingoptions)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image)
* assembly [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
