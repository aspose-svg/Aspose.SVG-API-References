---
title: "RendererTSource クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.Renderer1TSource クラス。すべてのレンダラーの基底抽象クラスです。"
type: docs
weight: 5070
url: /ja/net/aspose.svg.rendering/renderer-1/
---
## Renderer<TSource> class

すべてのレンダラーの基底抽象クラスです。

```csharp
public abstract class Renderer<TSource> : Renderer
```

| パラメータ | 説明 |
| --- | --- |
| TSource | ソースの型です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.svg.rendering/renderer/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_3)(*[IDevice](../idevice/), TSource*) | 指定された [`IDevice`](../idevice/) に *TSource* をレンダリングするメソッドを定義します。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_6)(*[IDevice](../idevice/), params TSource[]*) | 特定の [`IDevice`](../idevice/) に複数の *TSource* をレンダリングするメソッドを定義します。 |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_1)(*[IDevice](../idevice/), CancellationToken, params TSource[]*) | 特定の [`IDevice`](../idevice/) に複数の *TSource* をレンダリングするメソッドを定義します。操作のキャンセルを要求するためにキャンセルトークンを使用します。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render)(*[IDevice](../idevice/), int, params TSource[]*) | 特定の [`IDevice`](../idevice/) に複数の *TSource* をレンダリングするメソッドを定義します。 |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_2)(*[IDevice](../idevice/), TimeSpan, params TSource[]*) | 特定の [`IDevice`](../idevice/) に複数の *TSource* をレンダリングするメソッドを定義します。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_4)(*[IDevice](../idevice/), TSource, int*) | 指定された [`IDevice`](../idevice/) に *TSource* をレンダリングするメソッドを定義します。 |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_5)(*[IDevice](../idevice/), TSource, TimeSpan*) | 指定された [`IDevice`](../idevice/) に *TSource* をレンダリングするメソッドを定義します。 |

### 参照

* class [Renderer](../renderer/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
