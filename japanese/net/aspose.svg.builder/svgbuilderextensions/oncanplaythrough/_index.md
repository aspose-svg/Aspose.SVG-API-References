---
title: "SVGBuilderExtensions.OnCanPlayThrough"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnCanPlayThrough メソッド。中断なしでメディアの再生可能性を処理するために oncanplaythrough イベント属性を設定します。"
type: docs
weight: 1230
url: /ja/net/aspose.svg.builder/svgbuilderextensions/oncanplaythrough/
---
## SVGBuilderExtensions.OnCanPlayThrough<TBuilder> method

中断なしでメディアの再生可能性を処理するために、'oncanplaythrough' イベント属性を設定します。

```csharp
public static TBuilder OnCanPlayThrough<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | メディアがバッファリングで停止せずに最後まで再生できるときに実行する JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
