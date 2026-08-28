---
title: "SVGBuilderExtensions.OnSeeked"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnSeeked メソッド。メディアのシーク操作が完了したときのイベントを処理するための onseeked イベント属性を設定します。"
type: docs
weight: 1740
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onseeked/
---
## SVGBuilderExtensions.OnSeeked<TBuilder> method

'onseeked' イベント属性を設定し、メディアのシーク操作が完了したときのイベントを処理します。

```csharp
public static TBuilder OnSeeked<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | シーク操作が完了したときに実行する JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
