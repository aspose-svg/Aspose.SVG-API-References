---
title: "SvgRenderer.Render"
second_title: "Aspose.SVG for .NET API 参考"
description: "SvgRenderer Render 方法。定义用于将多个 SVGDocuments 渲染到特定 IDevice 的方法。"
type: docs
weight: 20
url: /zh/net/aspose.svg.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

定义将多个 [`SVGDocument`](../../../aspose.svg/svgdocument/)s 渲染到特定 [`IDevice`](../../idevice/) 的方法。

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 超时 | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |
| 源 | SVGDocument[] | 要渲染的 SVG 文档。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

定义一种方法，将多个 [`SVGDocument`](../../../aspose.svg/svgdocument/)s 渲染到特定 [`IDevice`](../../idevice/)，并使用取消令牌来请求取消操作。

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| cancellationToken | CancellationToken | 在等待任务完成期间要观察的取消令牌。 |
| 源 | SVGDocument[] | 要渲染的 SVG 文档。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
