---
title: "SvgRenderer クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.SvgRenderer クラス。SVG ドキュメントレンダラを表します。"
type: docs
weight: 5100
url: /ja/net/aspose.svg.rendering/svgrenderer/
---
## SvgRenderer class

SVG ドキュメント レンダラーを表します。

```csharp
public class SvgRenderer : Renderer<SVGDocument>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.svg.rendering/renderer/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.svg/svgdocument/)*) |  |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), params SVGDocument[]*) |  |
| override [Render](../../aspose.svg.rendering/svgrenderer/render/#render_5)(*[IDevice](../idevice/), CancellationToken, params SVGDocument[]*) | 複数の[`SVGDocument`](../../aspose.svg/svgdocument/)s を特定の[`IDevice`](../idevice/) にレンダリングするメソッドを定義し、キャンセルトークンを使用して操作のキャンセルを要求します。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), int, params SVGDocument[]*) |  |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.svg/svgdocument/), int*) |  |
| [Render](../../aspose.svg.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.svg/svgdocument/), TimeSpan*) |  |
| override [Render](../../aspose.svg.rendering/svgrenderer/render/#render_6)(*[IDevice](../idevice/), TimeSpan, params SVGDocument[]*) | 特定の[`IDevice`](../idevice/) に複数の[`SVGDocument`](../../aspose.svg/svgdocument/)s をレンダリングするメソッドを定義します。 |

### 参照

* class [SVGDocument](../../aspose.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
