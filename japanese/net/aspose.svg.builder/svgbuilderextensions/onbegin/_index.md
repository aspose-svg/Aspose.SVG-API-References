---
title: "SVGBuilderExtensions.OnBegin"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnBegin メソッド。アニメーション開始時に実行されるスクリプトを定義する onbegin 属性を設定します"
type: docs
weight: 1200
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onbegin/
---
## SVGBuilderExtensions.OnBegin<TBuilder> method

アニメーションの開始時に実行されるスクリプトを定義するために、'onbegin' 属性を設定します。

```csharp
public static TBuilder OnBegin<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IAnimationEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーションが開始したときに実行されるスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationEventAttributeSetter](../../ianimationeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
