---
title: "SvgRenderer 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.SvgRenderer 类。表示 SVG 文档渲染器"
type: docs
weight: 5100
url: /zh/net/aspose.svg.rendering/svgrenderer/
---
## SvgRenderer class

表示 SVG 文档渲染器。

```csharp
public class SvgRenderer : Renderer<SVGDocument>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.svg.rendering/renderer/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.svg/svgdocument/)*) |  |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), params SVGDocument[]*) |  |
| override [Render](../../aspose.svg.rendering/svgrenderer/render/#render_5)(*[IDevice](../idevice/), CancellationToken, params SVGDocument[]*) | 定义一个方法，用于将多个[`SVGDocument`](../../aspose.svg/svgdocument/)渲染到特定的[`IDevice`](../idevice/)，使用取消令牌来请求取消该操作。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), int, params SVGDocument[]*) |  |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.svg/svgdocument/), int*) |  |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.svg/svgdocument/), TimeSpan*) |  |
| override [Render](../../aspose.svg.rendering/svgrenderer/render/#render_6)(*[IDevice](../idevice/), TimeSpan, params SVGDocument[]*) | 定义方法，将多个[`SVGDocument`](../../aspose.svg/svgdocument/)渲染到特定的[`IDevice`](../idevice/)。 |

### 另请参阅

* class [SVGDocument](../../aspose.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
