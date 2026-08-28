---
title: "SVGBuilderExtensions.Transform"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Transform メソッド。SVG 要素の transform 属性を設定します。"
type: docs
weight: 2260
url: /ja/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

SVG 要素の 'transform' 属性を設定します。

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | SVG の変換を構成する関数。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
