---
title: "SVGBuilderExtensions.KeySplines"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions KeySplines メソッド。アニメーションのペース設定の制御点を指定する keySplines 属性を設定します。"
type: docs
weight: 1060
url: /ja/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

'keySplines' 属性を設定し、アニメーションのペースングの制御点を指定します。

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| buildSplines | スプライン構成を構築するアクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
