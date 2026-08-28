---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions RequiredExtensions メソッド。SVG 要素の requiredExtensions 属性を設定します。この属性は、SVG ドキュメントフラグメントを処理するために必要な拡張機能を指定します。"
type: docs
weight: 1970
url: /ja/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

SVG 要素に 'requiredExtensions' 属性を設定します。この属性は、SVG ドキュメントフラグメントの処理に必要な拡張機能を指定します。

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | 属性が設定される SVG 要素ビルダーです。 |
| value | 必要な拡張機能を表す文字列値。 |

### 戻り値

メソッドチェーン用の元の SVG 要素ビルダーです。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
