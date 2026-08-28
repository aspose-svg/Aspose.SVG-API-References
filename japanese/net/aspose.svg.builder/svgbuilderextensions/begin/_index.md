---
title: "SVGBuilderExtensions.Begin"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Begin メソッド。アニメーションの開始時点を定義する begin 属性を設定します。"
type: docs
weight: 610
url: /ja/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

'begin' 属性を設定し、アニメーションの開始時点を定義します。

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| 構成 | タイミング値を設定するデリゲートです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
