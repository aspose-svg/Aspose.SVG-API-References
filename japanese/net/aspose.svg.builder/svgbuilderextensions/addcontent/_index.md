---
title: "SVGBuilderExtensions.AddContent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddContent メソッド。SVG 要素にテキストコンテンツを追加します。"
type: docs
weight: 90
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

SVG 要素にテキスト コンテンツを追加します。

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| テキスト | 要素に追加されるテキストです。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドはテキストコンテンツを SVG 要素に直接追加できるようにします。テキストデータを含む要素に便利です。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
