---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddRadialGradient メソッド。ビルダーに radialGradient 要素の構成を追加します。"
type: docs
weight: 440
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

ビルダーに 'radialGradient' 要素の構成を追加します。

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | ‘radialGradient’ 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

SVG ビルダーに 'radialGradient' 要素を追加し、中心、半径、焦点、およびその他のグラデーションプロパティを指定します。

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | ‘radialGradient’ 要素が追加される SVG ビルダーインスタンスです。 |
| cx | グラデーションの中心の x 座標です。double または LengthType を持つ ValueTuple を指定できます。省略可能なパラメーターです。 |
| cy | グラデーションの中心の y 座標です。double または LengthType を持つ ValueTuple を指定できます。省略可能なパラメーターです。 |
| r | グラデーションの半径です。double または LengthType を持つ ValueTuple を指定できます。省略可能なパラメーターです。 |
| fx | グラデーションの焦点の x 座標です。double または LengthType を持つ ValueTuple を指定できます。省略可能なパラメーターです。 |
| fy | グラデーションの焦点の y 座標です。double または LengthType を持つ ValueTuple を指定できます。省略可能なパラメーターです。 |
| gradientUnits | グラデーションの座標系を指定します。省略可能なパラメーターです。 |
| spreadMethod | グラデーションが開始点と終了点を超えてどのように広がるかを定義します。省略可能なパラメーターです。 |
| href | 該当する場合、別のグラデーションへの参照です。オプション パラメーター。 |
| id | グラデーション要素の一意の識別子です。オプション パラメーター。 |
| extend | 放射状グラデーション要素ビルダーをさらに構成するためのオプション アクションです。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
