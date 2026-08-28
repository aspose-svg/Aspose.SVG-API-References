---
title: "SVGBuilderExtensions.SystemLanguage"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions SystemLanguage メソッド。SVG 要素の systemLanguage 属性を設定します。この属性は、SVG ドキュメント フラグメントが対象とする言語設定を指定します。"
type: docs
weight: 2170
url: /ja/net/aspose.svg.builder/svgbuilderextensions/systemlanguage/
---
## SVGBuilderExtensions.SystemLanguage<TBuilder> method

SVG 要素に 'systemLanguage' 属性を設定します。この属性は、SVG ドキュメントフラグメントが対象とする言語設定を指定します。

```csharp
public static TBuilder SystemLanguage<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | 属性が設定される SVG 要素ビルダーです。 |
| value | 言語設定を表す文字列値で、通常は言語タグの形式です。 |

### 戻り値

メソッドチェーン用の元の SVG 要素ビルダーです。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
