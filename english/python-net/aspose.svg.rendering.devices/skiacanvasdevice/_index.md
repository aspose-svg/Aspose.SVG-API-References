﻿---
title: SkiaCanvasDevice class
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.svg.rendering.devices/skiacanvasdevice/
is_root: false
---

## SkiaCanvasDevice class



**Inheritance:** [`SkiaCanvasDevice`](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice) → 
[`DeviceAdapter`](/svg/python-net/aspose.svg.rendering/deviceadapter) → 
[`Device`](/svg/python-net/aspose.svg.rendering/device)



The SkiaCanvasDevice type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/__init__/#aspose.svg.rendering.RenderingOptions-aspose.svg.rendering.devices.ISkiaCanvasProvider) | Constructs a new instance of SkiaCanvasDevice |
| [__init__](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/__init__/#aspose.svg.rendering.IDevice) | Initializes a new instance of the [`DeviceAdapter`](/svg/python-net/aspose.svg.rendering/deviceadapter) class. |


### Properties
| Property | Description |
| :- | :- |
| [adapted_device](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/adapted_device) | Gets or sets the adapted device. See [`IDevice`](/svg/python-net/aspose.svg.rendering/idevice). |
| [options](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/options) | Gets the rendering options. |
| [graphic_context](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/graphic_context) | Gets the graphic context. |


### Methods
| Method | Description |
| :- | :- |
| [save_graphic_context](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/save_graphic_context/#) | Pushes a copy of the entire graphics context onto the stack. |
| [restore_graphic_context](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/restore_graphic_context/#) | Restores the entire graphics context to its former value by popping it from the stack. |
| [begin_document](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/begin_document/#aspose.svg.dom.Document) | Begins rendering of the document. |
| [end_document](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/end_document/#) | Ends rendering of the document. |
| [begin_page](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/begin_page/#aspose.pydrawing.SizeF) | Begins rendering of the new page. |
| [end_page](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/end_page/#) | Ends rendering of the current page. |
| [begin_element](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/begin_element/#aspose.svg.dom.Element-aspose.pydrawing.RectangleF) | Begins rendering of the element. |
| [end_element](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/end_element/#aspose.svg.dom.Element) | Ends rendering of the element. |
| [close_path](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/close_path/#) | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. 
| [move_to](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/move_to/#aspose.pydrawing.PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. 
| [line_to](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/line_to/#aspose.pydrawing.PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [add_rect](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/add_rect/#aspose.pydrawing.RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [cubic_bezier_to](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/cubic_bezier_to/#aspose.pydrawing.PointF-aspose.pydrawing.PointF-aspose.pydrawing.PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2,
| [stroke](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/stroke/#) | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, 
| [fill](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/fill/#aspose.svg.drawing.FillRule) | Fills the entire region enclosed by the current path. 
| [clip](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/clip/#aspose.svg.drawing.FillRule) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. 
| [stroke_and_fill](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/stroke_and_fill/#aspose.svg.drawing.FillRule) | Strokes and fill current path.
| [fill_text](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/fill_text/#str-aspose.pydrawing.PointF) | Fills the specified text string at the specified location. |
| [stroke_text](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/stroke_text/#str-aspose.pydrawing.PointF) | Strokes the specified text string at the specified location. |
| [draw_image](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/draw_image/#bytes-aspose.svg.drawing.WebImageFormat-aspose.pydrawing.RectangleF) | Draws the specified image. |
| [flush](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice/flush/#) | Flushes all data to output stream. |



### See Also
* module [`aspose.svg.rendering.devices`](..)
* class [`Device`](/svg/python-net/aspose.svg.rendering/device)
* class [`DeviceAdapter`](/svg/python-net/aspose.svg.rendering/deviceadapter)
* class [`IDevice`](/svg/python-net/aspose.svg.rendering/idevice)
* class [`SkiaCanvasDevice`](/svg/python-net/aspose.svg.rendering.devices/skiacanvasdevice)