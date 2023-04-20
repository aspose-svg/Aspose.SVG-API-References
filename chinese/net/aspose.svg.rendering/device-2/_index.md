---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: Aspose.SVG for .NET API 参考
description: Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions 班级. 表示实现特定渲染设备的基类
type: docs
weight: 2740
url: /zh/net/aspose.svg.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

表示实现特定渲染设备的基类。

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| 范围 | 描述 |
| --- | --- |
| TGraphicContext | 保存当前图形控制参数的图形上下文 |
| TRenderingOptions | 渲染选项 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | 获取图形上下文 |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | 获取渲染选项。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [AddRect](../../aspose.svg.rendering/device-2/addrect/)(RectangleF) | 将一个矩形附加到当前路径作为一个完整的子路径。 |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(Document) | 开始呈现文档。 |
| abstract [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(Element, RectangleF) | 开始渲染节点。 |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(SizeF) | 开始呈现新页面。 |
| abstract [Clip](../../aspose.svg.rendering/device-2/clip/)(FillMode) | 通过将当前路径与当前路径相交来修改当前剪切路径，使用 FillMode 规则来确定要填充的区域。 此方法终止当前路径。 |
| abstract [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | 通过从当前点到子路径起点附加一条直线段来关闭当前子路径。 如果当前子路径已经关闭，则“ClosePath”不执行任何操作。 此运算符终止当前子路径。将另一个段附加到当前路径开始一个新的子路径， ，即使新段开始于“ClosePath”方法到达的端点。 |
| abstract [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | 将三次贝塞尔曲线附加到当前路径。曲线从当前点延伸到点 pt2, ，使用 pt1 和 pt2 作为贝塞尔控制点。新的当前点是 pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | 执行与释放、释放或重置非托管资源相关的应用程序定义的任务。 |
| abstract [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | 绘制指定图像。 |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | 结束文档呈现。 |
| abstract [EndElement](../../aspose.svg.rendering/device-2/endelement/)(Element) | 结束节点渲染。 |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | 结束当前页面的渲染。 |
| abstract [Fill](../../aspose.svg.rendering/device-2/fill/)(FillMode) | 填充当前路径包围的整个区域。 如果路径由多个断开连接的子路径组成，则填充所有子路径的内部， 一起考虑。 此方法终止当前路径。 |
| abstract [FillText](../../aspose.svg.rendering/device-2/filltext/)(string, PointF) | 在指定位置填充指定的文本字符串。 |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | 将所有数据刷新到输出流。 |
| abstract [LineTo](../../aspose.svg.rendering/device-2/lineto/)(PointF) | 从当前点到该点 (pt) 追加一条直线段。新的当前点是 pt. |
| abstract [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(PointF) | 通过将当前点移动到参数 pt 的坐标开始新的子路径，省略任何连接线段。 如果当前路径中之前的路径构造方法也是“MoveTo”，则新的“MoveTo”覆盖它； 路径中没有先前“MoveTo”操作的痕迹。 |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | 通过从堆栈中弹出它来将整个图形上下文恢复到它以前的值。 |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | 将整个图形上下文的副本推送到堆栈上。 |
| abstract [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | 沿当前路径画一条线。描边线跟随路径中的每个直线或曲线段， 以线段为中心，边与其平行。路径的每个子路径都被单独处理。 此方法终止当前路径。 |
| abstract [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(FillMode) | 描边并填充当前路径。 此方法终止当前路径。 |
| abstract [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(string, PointF) | 在指定位置描边指定的文本字符串。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | 表示设备的配置对象。 |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | 指定将页面写入输出流\流的策略类型。 |

### 也可以看看

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* 命名空间 [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* 部件 [Aspose.SVG](../../)


