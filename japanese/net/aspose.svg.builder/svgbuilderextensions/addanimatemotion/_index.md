---
title: "SVGBuilderExtensions.AddAnimateMotion"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddAnimateMotion メソッド。ビルダーに animateMotion 要素の構成を追加します。"
type: docs
weight: 40
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addanimatemotion/
---
## SVGBuilderExtensions.AddAnimateMotion<TBuilder> method

ビルダーに 'animateMotion' 要素の構成を追加します。

```csharp
public static TBuilder AddAnimateMotion<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateMotionElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 「animateMotion」要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGAnimateMotionElementBuilder](../../svganimatemotionelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
