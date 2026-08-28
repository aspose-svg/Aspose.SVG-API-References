---
title: "SVGBuilderExtensions.OnCanPlay"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnCanPlay メソッド。メディアの再生可能性チェックを処理するための oncanplay イベント属性を設定します。"
type: docs
weight: 1220
url: /ja/net/aspose.svg.builder/svgbuilderextensions/oncanplay/
---
## SVGBuilderExtensions.OnCanPlay<TBuilder> method

メディアの再生可能性チェックを処理するために、'oncanplay' イベント属性を設定します。

```csharp
public static TBuilder OnCanPlay<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | メディアの再生が可能になったときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
