---
title: Class PdfDevice
second_title: Aspose.SVG for .NET API 参考
description: Aspose.Svg.Rendering.Pdf.PdfDevice 班级. 表示渲染到pdf文档
type: docs
weight: 2950
url: /zh/net/aspose.svg.rendering.pdf/pdfdevice/
---
## PdfDevice class

表示渲染到pdf文档。

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | 初始化一个新的实例`PdfDevice`类. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | 初始化一个新的实例`PdfDevice`类. |
| [PdfDevice](pdfdevice/#constructor_5)(string) | 初始化一个新的实例`PdfDevice`类. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | 初始化一个新的实例`PdfDevice`按渲染选项和流提供程序分类。 |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | 初始化一个新的实例`PdfDevice`按渲染选项和输出流分类。 |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, string) | 初始化一个新的实例`PdfDevice`按渲染选项和输出文件名分类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [AddRect](../../aspose.svg.rendering.pdf/pdfdevice/addrect/)(RectangleF) | 将一个矩形附加到当前路径作为一个完整的子路径。 |
| override [BeginDocument](../../aspose.svg.rendering.pdf/pdfdevice/begindocument/)(Document) | 开始呈现文档。 |
| override [BeginElement](../../aspose.svg.rendering.pdf/pdfdevice/beginelement/)(Element, RectangleF) | 开始渲染元素。 |
| override [BeginPage](../../aspose.svg.rendering.pdf/pdfdevice/beginpage/)(SizeF) | 开始呈现新页面。 |
| override [Clip](../../aspose.svg.rendering.pdf/pdfdevice/clip/)(FillMode) | 通过将当前路径与当前路径相交来修改当前剪切路径，使用 FillMode 规则来确定要填充的区域。 此方法终止当前路径。 |
| override [ClosePath](../../aspose.svg.rendering.pdf/pdfdevice/closepath/)() | 通过从当前点到子路径起点附加一条直线段来关闭当前子路径。 如果当前子路径已经关闭，则“ClosePath”不执行任何操作。 此运算符终止当前子路径。将另一个段附加到当前路径开始一个新的子路径， ，即使新段开始于“ClosePath”方法到达的端点。 |
| override [CubicBezierTo](../../aspose.svg.rendering.pdf/pdfdevice/cubicbezierto/)(PointF, PointF, PointF) | 将三次贝塞尔曲线附加到当前路径。曲线从当前点延伸到点 pt2, ，使用 pt1 和 pt2 作为贝塞尔控制点。新的当前点是 pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.svg.rendering.pdf/pdfdevice/drawimage/)(byte[], ImageType, RectangleF) | 绘制指定图像。 |
| override [EndDocument](../../aspose.svg.rendering.pdf/pdfdevice/enddocument/)() | 结束文档呈现。 |
| override [EndElement](../../aspose.svg.rendering.pdf/pdfdevice/endelement/)(Element) | 结束元素的渲染。 |
| override [EndPage](../../aspose.svg.rendering.pdf/pdfdevice/endpage/)() | 结束当前页面的渲染。 |
| override [Fill](../../aspose.svg.rendering.pdf/pdfdevice/fill/)(FillMode) | 填充当前路径包围的整个区域。 如果路径由多个断开连接的子路径组成，则填充所有子路径的内部， 一起考虑。 此方法终止当前路径。 |
| override [FillText](../../aspose.svg.rendering.pdf/pdfdevice/filltext/)(string, PointF) | 在指定位置填充指定的文本字符串。 |
| override [Flush](../../aspose.svg.rendering.pdf/pdfdevice/flush/)() | 将所有数据刷新到输出流。 |
| override [LineTo](../../aspose.svg.rendering.pdf/pdfdevice/lineto/)(PointF) | 从当前点到该点 (pt) 追加一条直线段。新的当前点是 pt. |
| override [MoveTo](../../aspose.svg.rendering.pdf/pdfdevice/moveto/)(PointF) | 通过将当前点移动到参数 pt 的坐标开始新的子路径，省略任何连接线段。 如果当前路径中之前的路径构造方法也是“MoveTo”，则新的“MoveTo”覆盖它； 路径中没有先前“MoveTo”操作的痕迹。 |
| override [RestoreGraphicContext](../../aspose.svg.rendering.pdf/pdfdevice/restoregraphiccontext/)() | 通过从堆栈中弹出它来将整个图形上下文恢复到它以前的值。 |
| override [SaveGraphicContext](../../aspose.svg.rendering.pdf/pdfdevice/savegraphiccontext/)() | 将整个图形上下文的副本推送到堆栈上。 |
| override [Stroke](../../aspose.svg.rendering.pdf/pdfdevice/stroke/)() | 沿当前路径画一条线。描边线跟随路径中的每个直线或曲线段， 以线段为中心，边与其平行。路径的每个子路径都被单独处理。 此方法终止当前路径。 |
| override [StrokeAndFill](../../aspose.svg.rendering.pdf/pdfdevice/strokeandfill/)(FillMode) | 描边并填充当前路径。 此方法终止当前路径。 |
| override [StrokeText](../../aspose.svg.rendering.pdf/pdfdevice/stroketext/)(string, PointF) | 在指定位置描边指定的文本字符串。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| class [PdfGraphicContext](pdfdevice.pdfgraphiccontext/) | 保存 PdfDevice 的当前图形控制参数。 这些参数定义了图形运算符执行的全局框架。 |

### 也可以看看

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* 命名空间 [Aspose.Svg.Rendering.Pdf](../../aspose.svg.rendering.pdf/)
* 部件 [Aspose.SVG](../../)


