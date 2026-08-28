---
title: "SVGBuilderExtensions.By"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions By メソッド。指定された長さタイプでアニメーションの相対オフセット値を定義する by 属性を設定します。"
type: docs
weight: 620
url: /ja/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

'by' 属性を設定し、指定された長さタイプでアニメーションの相対オフセット値を定義します。

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーションの相対オフセット値。 |
| type | 「by」値の長さタイプ。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
