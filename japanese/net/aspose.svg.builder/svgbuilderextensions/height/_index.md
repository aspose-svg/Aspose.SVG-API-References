---
title: "SVGBuilderExtensions.Height"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Height メソッド。SVG 要素の height 属性を設定します。"
type: docs
weight: 1000
url: /ja/net/aspose.svg.builder/svgbuilderextensions/height/
---
## SVGBuilderExtensions.Height<TBuilder> method

SVG要素の 'height' 属性を設定します。

```csharp
public static TBuilder Height<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IHeightAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 'height' 属性の値です。 |
| type | 長さ測定のタイプです（デフォルトはピクセル）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IHeightAttributeSetter](../../iheightattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
