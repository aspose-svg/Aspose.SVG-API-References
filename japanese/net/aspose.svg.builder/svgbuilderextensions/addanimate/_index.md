---
title: "SVGBuilderExtensions.AddAnimate"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddAnimate メソッド。ビルダーに animate 要素の構成を追加します。"
type: docs
weight: 30
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addanimate/
---
## SVGBuilderExtensions.AddAnimate<TBuilder> method

ビルダーに 'animate' 要素の構成を追加します。

```csharp
public static TBuilder AddAnimate<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 |  'animate' 要素の構成アクション。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGAnimateElementBuilder](../../svganimateelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
