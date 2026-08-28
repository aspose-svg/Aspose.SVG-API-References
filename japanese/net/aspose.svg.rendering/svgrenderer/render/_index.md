---
title: "SvgRenderer.Render"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SvgRenderer Render メソッド。複数の SVGDocument を特定の IDevice にレンダリングするメソッドを定義します。"
type: docs
weight: 20
url: /ja/net/aspose.svg.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

複数の [`SVGDocument`](../../../aspose.svg/svgdocument/)s を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを表す -1 ミリ秒の TimeSpan です。 |
| ソース | SVGDocument[] | レンダリングする SVG ドキュメント。 |

### 参照

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

複数の [`SVGDocument`](../../../aspose.svg/svgdocument/)s を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義し、操作のキャンセルを要求するためにキャンセルトークンを使用します。

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| cancellationToken | CancellationToken | タスクの完了を待機中に監視するキャンセルトークン。 |
| ソース | SVGDocument[] | レンダリングする SVG ドキュメント。 |

### 参照

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
