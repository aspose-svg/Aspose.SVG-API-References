---
title: "SVGBuilderExtensions.To"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions To メソッド。指定された長さタイプでアニメーションの終了値を定義する to 属性を設定します"
type: docs
weight: 2250
url: /ja/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

'to' 属性を設定し、指定された長さタイプでアニメーションの終了値を定義します。

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーションの終了値。 |
| type | 'to' 値の長さタイプ。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
