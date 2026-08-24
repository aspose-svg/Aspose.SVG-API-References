---
title: "XpsDevice.XpsGraphicContext 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Xps.XpsDeviceXpsGraphicContext 类。保存 XpsDevice 的当前图形控制参数。这些参数定义了图形操作符执行的全局框架"
type: docs
weight: 5130
url: /zh/net/aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext/
---
## XpsDevice.XpsGraphicContext class

保存 XpsDevice 的当前图形控制参数。这些参数定义了图形操作符执行的全局框架。

```csharp
public class XpsGraphicContext : GraphicContext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XpsGraphicContext](../../aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext/.ctor)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing/) { get; set; } | 设置或获取字符间距。 |
| [CurrentElement](../../aspose.svg.rendering/graphiccontext/currentelement/) { get; } | 获取当前处理的元素。 |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush/) { get; set; } | 设置或获取用于填充路径内部的画笔对象。 |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font/) { get; set; } | 设置或获取用于渲染文本的 TrueType 字体对象。 |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize/) { get; set; } | 设置或获取文本字体大小。 |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle/) { get; set; } | 设置或获取文本字体样式。 |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap/) { get; set; } | 设置或获取指定任何被描边的开放路径端点形状的代码。 |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset/) { get; set; } | 设置或获取当前线段虚线模式的相位偏移。 |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern/) { get; set; } | 设置或获取在描边路径时使用的虚线模式描述。可以将其设置为 null 或空数组以禁用。 |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin/) { get; set; } | 设置或获取指定已连接段之间接点形状的代码。 |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth/) { get; set; } | 设置或获取要描边的路径的粗细。 |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit/) { get; set; } | 设置或获取描边路径的斜接线连接的最大长度。此参数限制线段在锐角相接时产生的“尖刺”长度。 |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush/) { get; set; } | 设置或获取用于描边路径的画刷对象。 |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo/) { get; } | 获取一个 [`TextInfo`](../../aspose.svg.rendering/textinfo/) 对象，其中包含有关渲染文本的信息。 |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix/) { get; set; } | 设置或获取变换矩阵。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone/)() | 创建一个 GraphicContext 类的新实例，其属性值与现有实例相同。 |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform/)(*[IMatrix](../../aspose.svg.drawing/imatrix/)*) | 通过乘以指定矩阵来修改当前变换矩阵。 |

### 另请参阅

* class [GraphicContext](../../aspose.svg.rendering/graphiccontext/)
* class [XpsDevice](../xpsdevice/)
* namespace [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps/)
* assembly [Aspose.SVG](../../)
