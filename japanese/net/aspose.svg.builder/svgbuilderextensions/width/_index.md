---
title: "SVGBuilderExtensions.Width"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Width メソッド。SVG 要素の width 属性を設定します。"
type: docs
weight: 2330
url: /ja/net/aspose.svg.builder/svgbuilderextensions/width/
---
## SVGBuilderExtensions.Width<TBuilder> method

SVG 要素の 'width' 属性を設定します。

```csharp
public static TBuilder Width<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IWidthAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 'width' 属性の値です。 |
| type | 長さ測定のタイプです（デフォルトはピクセル）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IWidthAttributeSetter](../../iwidthattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
