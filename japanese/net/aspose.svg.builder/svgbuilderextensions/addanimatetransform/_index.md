---
title: "SVGBuilderExtensions.AddAnimateTransform"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddAnimateTransform メソッド。builder に animateTransform 要素の構成を追加します。"
type: docs
weight: 50
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addanimatetransform/
---
## SVGBuilderExtensions.AddAnimateTransform<TBuilder> method

ビルダーに 'animateTransform' 要素の構成を追加します。

```csharp
public static TBuilder AddAnimateTransform<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateTransformElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'animateTransform' 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGAnimateTransformElementBuilder](../../svganimatetransformelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
