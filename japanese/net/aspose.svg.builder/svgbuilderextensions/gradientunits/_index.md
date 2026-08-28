---
title: "SVGBuilderExtensions.GradientUnits"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions GradientUnits メソッド。グラデーション要素の gradientUnits 属性を設定します。"
type: docs
weight: 990
url: /ja/net/aspose.svg.builder/svgbuilderextensions/gradientunits/
---
## SVGBuilderExtensions.GradientUnits<TBuilder> method

グラデーション要素の 'gradientUnits' 属性を設定します。

```csharp
public static TBuilder GradientUnits<TBuilder>(this TBuilder builder, CoordinateUnits units)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | 属性が適用される SVG 要素ビルダー。 |
| 単位 | グラデーションの座標単位（userSpaceOnUse または objectBoundingBox）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [CoordinateUnits](../../coordinateunits/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
