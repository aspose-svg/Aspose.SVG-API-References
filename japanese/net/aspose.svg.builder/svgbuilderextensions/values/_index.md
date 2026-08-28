---
title: "SVGBuilderExtensions.Values"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Values メソッド。アニメーションの間に使用される値のセットを指定する values 属性を設定します。"
type: docs
weight: 2290
url: /ja/net/aspose.svg.builder/svgbuilderextensions/values/
---
## SVGBuilderExtensions.Values<TBuilder> method

'values' 属性を設定し、アニメーション中に使用される値のセットを指定します。

```csharp
public static TBuilder Values<TBuilder>(this TBuilder builder, params string[] values)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| values | アニメーション用の値の配列。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
