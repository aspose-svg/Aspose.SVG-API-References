---
title: "SVGBuilderExtensions.End"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions End メソッド。アニメーションが終了すべき時点を定義する end 属性を設定します。"
type: docs
weight: 790
url: /ja/net/aspose.svg.builder/svgbuilderextensions/end/
---
## SVGBuilderExtensions.End<TBuilder> method

'end' 属性を設定し、アニメーションが終了するタイミングを定義します。

```csharp
public static TBuilder End<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
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
