---
title: "RendererTSource 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Renderer1TSource 类。所有渲染器的基抽象类。"
type: docs
weight: 5070
url: /zh/net/aspose.svg.rendering/renderer-1/
---
## Renderer<TSource> class

所有渲染器的基抽象类。

```csharp
public abstract class Renderer<TSource> : Renderer
```

| 参数 | 描述 |
| --- | --- |
| TSource | 源的类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.svg.rendering/renderer/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_3)(*[IDevice](../idevice/), TSource*) | 定义将 *TSource* 渲染到指定的 [`IDevice`](../idevice/) 的方法。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_6)(*[IDevice](../idevice/), params TSource[]*) | 定义将多个 *TSource* 渲染到特定的 [`IDevice`](../idevice/) 的方法。 |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_1)(*[IDevice](../idevice/), CancellationToken, params TSource[]*) | 定义一种方法，将多个 *TSource* 渲染到特定的 [`IDevice`](../idevice/)，并使用取消令牌请求取消操作。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render)(*[IDevice](../idevice/), int, params TSource[]*) | 定义将多个 *TSource* 渲染到特定的 [`IDevice`](../idevice/) 的方法。 |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_2)(*[IDevice](../idevice/), TimeSpan, params TSource[]*) | 定义将多个 *TSource* 渲染到特定的 [`IDevice`](../idevice/) 的方法。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_4)(*[IDevice](../idevice/), TSource, int*) | 定义将 *TSource* 渲染到指定的 [`IDevice`](../idevice/) 的方法。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_5)(*[IDevice](../idevice/), TSource, TimeSpan*) | 定义将 *TSource* 渲染到指定的 [`IDevice`](../idevice/) 的方法。 |

### 另请参阅

* class [Renderer](../renderer/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
