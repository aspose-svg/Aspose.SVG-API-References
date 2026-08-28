---
title: "SVGBuilderExtensions.OnDurationChange"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnDurationChange メソッド。メディアの再生時間の変化を処理するための ondurationchange イベント属性を設定します。"
type: docs
weight: 1390
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ondurationchange/
---
## SVGBuilderExtensions.OnDurationChange<TBuilder> method

'ondurationchange' イベント属性を設定し、メディアの長さの変化を処理します。

```csharp
public static TBuilder OnDurationChange<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | メディアの再生時間が変化したときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
