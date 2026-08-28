---
title: "SVGBuilderExtensions.Intercept"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Intercept メソッド。コンポーネント転送関数要素の intercept 属性を設定します。"
type: docs
weight: 1050
url: /ja/net/aspose.svg.builder/svgbuilderextensions/intercept/
---
## SVGBuilderExtensions.Intercept<TBuilder> method

コンポーネント転送関数要素の 'intercept' 属性を設定します。

```csharp
public static TBuilder Intercept<TBuilder>(this TBuilder builder, double intercept)
    where TBuilder : ISVGElementBuilder, ITransferFunctionAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| intercept | 転送関数の intercept 値。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransferFunctionAttributeSetter](../../itransferfunctionattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
