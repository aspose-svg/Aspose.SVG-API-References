---
title: "SVGBuilderExtensions.AddFilter"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddFilter メソッド。builder にフィルター要素の構成を追加します"
type: docs
weight: 300
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

ビルダーに 'filter' 要素の構成を追加します。

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'filter' 要素の構成アクション。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

SVG ビルダーに 'filter' 要素を追加し、SVG 要素に適用できるフィルター効果を定義します。

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | 'filter' 要素が追加される SVG ビルダーインスタンス。 |
| filterUnits | フィルターの x、y、width、height 属性の座標系を指定します。省略可能なパラメーターです。 |
| primitiveUnits | フィルターの子要素属性の座標系を指定します。省略可能なパラメーターです。 |
| x | フィルター領域の x 座標。double または LengthType を持つ ValueTuple にできます。省略可能なパラメーターです。 |
| y | フィルター領域の y 座標。double または LengthType を持つ ValueTuple にできます。省略可能なパラメーターです。 |
| width | フィルタ領域の幅。double または LengthType を持つ ValueTuple にすることができます。オプション パラメータ。 |
| height | フィルタ領域の高さ。double または LengthType を持つ ValueTuple にすることができます。オプション パラメータ。 |
| fill | フィルタ要素の塗りつぶしカラーまたはペイント。オプション パラメータ。 |
| stroke | フィルタ要素のストロークカラーまたはペイント。オプション パラメータ。 |
| id | フィルタ要素の一意の識別子。オプション パラメータ。 |
| extend | SVGFilterElementBuilder をさらに構成するためのオプション アクション。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
