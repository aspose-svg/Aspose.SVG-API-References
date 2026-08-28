---
title: "SVGBuilderExtensions.AddBuilder"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddBuilder メソッド。既存の SVG 要素ビルダーを現在の SVG 要素ビルダーに追加します。このメソッドは、事前定義された SVG 要素ビルダーを現在のビルダーに組み込むために使用されます。"
type: docs
weight: 60
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

既存の SVG 要素ビルダーを現在の SVG 要素ビルダーに追加します。このメソッドは、事前定義された SVG 要素ビルダーを現在のビルダーに組み込むために使用されます。

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| TElementBuilder | 構成対象の SVG 要素ビルダーの型です。TElementBuilder は ISVGElementBuilder を実装している必要があります。 |
| ビルダー | 他の要素ビルダーが追加される SVG 要素ビルダーです。 |
| elementBuilder | 追加される SVG 要素ビルダーです。 |

### 戻り値

メソッドチェーン用の元の SVG 要素ビルダーです。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
