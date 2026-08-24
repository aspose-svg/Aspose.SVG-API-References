---
title: "IDevice 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.IDevice 接口。定义支持自定义渲染路径、文本和图像等图形元素的方法和属性"
type: docs
weight: 4890
url: /zh/net/aspose.svg.rendering/idevice/
---
## IDevice interface

定义支持对路径、文本和图像等图形元素进行自定义渲染的方法和属性。

```csharp
public interface IDevice : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | 获取图形上下文。 |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | 获取渲染选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(*RectangleF*) | 将矩形追加到当前路径，作为完整的子路径。 |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | 开始渲染文档。 |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | 开始渲染元素。 |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(*SizeF*) | 开始渲染新页面。 |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 通过将当前剪裁路径与当前路径相交来修改剪裁路径，使用 FillRule 确定填充区域。此方法会终止当前路径。 |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | 通过从当前点到子路径起始点追加一条直线段来关闭当前子路径。如果当前子路径已经关闭，"ClosePath" 不执行任何操作。此操作符会终止当前子路径。向当前路径追加另一段会开始一个新子路径，即使新段的起点是由 "ClosePath" 方法达到的端点。 |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | 向当前路径追加三次 Bézier 曲线。该曲线从当前点延伸到点 pt3，使用 pt1 和 pt2 作为 Bézier 控制点。新的当前点为 pt3。 |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | 绘制指定的图像。 |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | 结束文档渲染。 |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | 结束元素渲染。 |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | 结束当前页面渲染。 |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 填充当前路径所围成的整个区域。如果路径由多个不相连的子路径组成，则一起填充所有子路径的内部。此方法会终止当前路径。 |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(*string, PointF*) | 在指定位置填充指定的文本字符串。 |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | 将所有数据刷新到输出流。 |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(*PointF*) | 追加一条从当前点到点 (pt) 的直线段。新的当前点为 pt。 |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(*PointF*) | 通过将当前点移动到参数 pt 的坐标来开始一个新子路径，省略任何连接线段。如果当前路径中先前的路径构造方法也是 "MoveTo"，则新的 "MoveTo" 会覆盖它；路径中不再保留先前的 "MoveTo" 操作的痕迹。 |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | 通过从堆栈弹出，恢复整个图形上下文到其先前的值。 |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | 将整个图形上下文的副本压入堆栈。 |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | 沿当前路径描边。描边线沿路径中的每条直线或曲线段绘制，居中于该段，两侧平行。路径的每个子路径分别处理。此方法会终止当前路径。 |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 对当前路径进行描边和填充。此方法会终止当前路径。 |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(*string, PointF*) | 在指定位置描绘指定的文本字符串。 |

### 另请参阅

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
