---
title: "SVGBuilderExtensions.GradientTransform"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions GradientTransform メソッド。グラデーション要素の gradientTransform 属性を設定します。"
type: docs
weight: 980
url: /ja/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

グラデーション要素の 'gradientTransform' 属性を設定します。

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | 属性が適用される SVG 要素ビルダー。 |
| 構成 | SVG 変換ビルダーを構成する関数。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
