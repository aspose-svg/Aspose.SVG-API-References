---
title: "DeviceTGraphicContextTRenderingOptions 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions 类。表示特定渲染设备实现的基类"
type: docs
weight: 4820
url: /zh/net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

表示特定渲染设备实现的基类。

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| 参数 | 描述 |
| --- | --- |
| TGraphicContext | 保存当前图形控制参数的图形上下文 |
| TRenderingOptions | 渲染选项 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | 获取图形上下文 |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | 获取渲染选项。 |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | 获取设备配置。 |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | 设置并获取输出流。 |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | 获取流提供程序对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | 将矩形追加到当前路径，作为完整的子路径。 |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | 开始渲染文档。 |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | 开始渲染节点。 |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | 开始渲染新页面。 |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 通过将当前剪裁路径与当前路径相交来修改剪裁路径，使用 FillRule 确定填充区域。此方法会终止当前路径。 |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | 通过从当前点到子路径起始点追加一条直线段来关闭当前子路径。如果当前子路径已经关闭，"ClosePath" 不执行任何操作。此操作符会终止当前子路径。向当前路径追加另一段会开始一个新子路径，即使新段的起点是由 "ClosePath" 方法达到的端点。 |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | 向当前路径追加一条三次贝塞尔曲线。该曲线从当前点延伸到点 pt2，使用 pt1 和 pt2 作为贝塞尔控制点。新的当前点为 pt3。 |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | 绘制指定的图像。 |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | 结束文档渲染。 |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | 结束节点渲染。 |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | 结束当前页面渲染。 |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 填充当前路径所围成的整个区域。如果路径由多个不相连的子路径组成，则一起填充所有子路径的内部。此方法会终止当前路径。 |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | 在指定位置填充指定的文本字符串。 |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | 将所有数据刷新到输出流。 |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | 追加一条从当前点到点 (pt) 的直线段。新的当前点为 pt。 |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | 通过将当前点移动到参数 pt 的坐标来开始一个新子路径，省略任何连接线段。如果当前路径中先前的路径构造方法也是 "MoveTo"，则新的 "MoveTo" 会覆盖它；路径中不再保留先前的 "MoveTo" 操作的痕迹。 |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | 通过从堆栈弹出，恢复整个图形上下文到其先前的值。 |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | 将整个图形上下文的副本压入堆栈。 |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | 沿当前路径描边。描边线沿路径中的每条直线或曲线段绘制，居中于该段，两侧平行。路径的每个子路径分别处理。此方法会终止当前路径。 |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 对当前路径进行描边和填充。此方法会终止当前路径。 |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | 在指定位置描绘指定的文本字符串。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | 表示设备的配置对象。 |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | 指定将页面写入输出流\streams 的策略类型。 |

### 另请参阅

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
