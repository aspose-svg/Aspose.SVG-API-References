---
title: "SVGBuilderExtensions.StrokeWidth"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions StrokeWidth メソッド。ストロークの幅を定義する SVG 要素の stroke-width 属性を設定します。"
type: docs
weight: 2150
url: /ja/net/aspose.svg.builder/svgbuilderextensions/strokewidth/
---
## SVGBuilderExtensions.StrokeWidth<TBuilder> method

SVG 要素の 'stroke-width' 属性を設定し、ストロークの幅を定義します。

```csharp
public static TBuilder StrokeWidth<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | ストローク幅の値です。 |
| type | ストローク幅の単位タイプです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
