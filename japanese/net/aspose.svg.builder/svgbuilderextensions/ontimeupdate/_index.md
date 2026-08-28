---
title: "SVGBuilderExtensions.OnTimeUpdate"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnTimeUpdate メソッド。メディアの現在の再生位置が変化したときに発生するイベントを処理する ontimeupdate イベント属性を設定します"
type: docs
weight: 1810
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ontimeupdate/
---
## SVGBuilderExtensions.OnTimeUpdate<TBuilder> method

'ontimeupdate' イベント属性を設定し、メディアの現在の再生位置が変化したときのイベントを処理します。

```csharp
public static TBuilder OnTimeUpdate<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 現在の再生位置が変化したときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
