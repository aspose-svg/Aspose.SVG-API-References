---
title: "SVGBuilderExtensions.StrokeDashoffset"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions StrokeDashoffset メソッド。ストロークダッシュ配列の開始位置を定義する stroke-dashoffset 属性を SVG 要素に設定します。"
type: docs
weight: 2100
url: /ja/net/aspose.svg.builder/svgbuilderextensions/strokedashoffset/
---
## SVGBuilderExtensions.StrokeDashoffset<TBuilder> method

SVG 要素の 'stroke-dashoffset' 属性を設定し、ストロークダッシュ配列の開始位置のオフセットを定義します。

```csharp
public static TBuilder StrokeDashoffset<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | ダッシュオフセット値。 |
| type | オフセット値の単位タイプ。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
