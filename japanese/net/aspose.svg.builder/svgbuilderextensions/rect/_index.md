---
title: "SVGBuilderExtensions.Rect"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Rect メソッド。SVG 要素の x、y、width、height 属性を設定して矩形を定義します。"
type: docs
weight: 1920
url: /ja/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

矩形を定義するために SVG 要素の 'x'、'y'、'width'、'height' 属性を設定します。

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| x | 矩形の x 座標です。 |
| y | 矩形の y 座標です。 |
| width | 矩形の幅。 |
| height | 矩形の高さ。 |
| type | すべての寸法の長さ測定タイプ（デフォルトはピクセル）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
