---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddLinearGradient メソッド。builder に linearGradient 要素の構成を追加します。"
type: docs
weight: 360
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

ビルダーに 'linearGradient' 要素の構成を追加します。

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | ‘linearGradient’ 要素の構成アクション。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

SVG ビルダーに 'linearGradient' 要素を追加し、その開始位置と終了位置、その他のグラデーションプロパティを指定します。

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | ‘linearGradient’ 要素が追加される SVG ビルダーインスタンス。 |
| x1 | グラデーションの開始 x 座標。double または LengthType を持つ ValueTuple にすることができます。 |
| y1 | グラデーションの開始 y 座標。double または LengthType を持つ ValueTuple にすることができます。 |
| x2 | グラデーションの終了 x 座標。double または LengthType を持つ ValueTuple にすることができます。 |
| y2 | グラデーションの終了 y 座標。double または LengthType を持つ ValueTuple にすることができます。 |
| gradientUnits | グラデーションの座標系を指定します。省略可能なパラメーターです。 |
| spreadMethod | グラデーションが開始点と終了点を超えてどのように広がるかを定義します。省略可能なパラメーターです。 |
| href | 該当する場合、別のグラデーションへの参照です。オプション パラメーター。 |
| id | グラデーション要素の一意の識別子です。オプション パラメーター。 |
| extend | 線形グラデーション要素ビルダーをさらに構成するためのオプションのアクション。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
