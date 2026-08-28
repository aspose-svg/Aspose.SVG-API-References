---
title: "SVGBuilderExtensions.OnShow"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnShow メソッド。コンテキストメニューが表示されたときにイベントを処理するために使用される onshow イベント属性を設定します。"
type: docs
weight: 1770
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onshow/
---
## SVGBuilderExtensions.OnShow<TBuilder> method

'onshow' イベント属性を設定し、通常はコンテキストメニューが表示されたときのイベントを処理するために使用されます。

```csharp
public static TBuilder OnShow<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | コンテキストメニューが表示されたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
