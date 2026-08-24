---
title: "XpsDevice 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Xps.XpsDevice 类。表示渲染到 XPS 文档。"
type: docs
weight: 5120
url: /zh/net/aspose.svg.rendering.xps/xpsdevice/
---
## XpsDevice class

表示渲染到 XPS 文档。

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(*[ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | 初始化 `XpsDevice` 类的新实例。 |
| [XpsDevice](xpsdevice/#constructor_4)(*Stream*) | 初始化 `XpsDevice` 类的新实例。 |
| [XpsDevice](xpsdevice/#constructor_5)(*string*) | 初始化 `XpsDevice` 类的新实例。 |
| [XpsDevice](xpsdevice/#constructor_1)(*[XpsRenderingOptions](../xpsrenderingoptions/), [ICreateStreamProvider](../../aspose.svg.io/icreatestreamprovider/)*) | 通过渲染选项和流提供程序初始化 `XpsDevice` 类的新实例。 |
| [XpsDevice](xpsdevice/#constructor_2)(*[XpsRenderingOptions](../xpsrenderingoptions/), Stream*) | 通过渲染选项和输出流初始化 `XpsDevice` 类的新实例。 |
| [XpsDevice](xpsdevice/#constructor_3)(*[XpsRenderingOptions](../xpsrenderingoptions/), string*) | 通过渲染选项和输出文件名初始化 `XpsDevice` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } |  |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } |  |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } |  |

## 方法

| 名称 | 描述 |
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

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [XpsGraphicContext](../../aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext) | 保存 XpsDevice 的当前图形控制参数。这些参数定义了图形操作符执行的全局框架。 |

### 另请参阅

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* namespace [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps/)
* assembly [Aspose.SVG](../../)
