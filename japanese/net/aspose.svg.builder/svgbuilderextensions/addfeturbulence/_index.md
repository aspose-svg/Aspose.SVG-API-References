---
title: "SVGBuilderExtensions.AddFeTurbulence"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddFeTurbulence メソッド。ビルダーに feTurbulence 要素の構成を追加します。この要素はパーリンノイズを使用して画像を生成し、雲や大理石のようなテクスチャの作成に役立ちます。"
type: docs
weight: 290
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addfeturbulence/
---
## AddFeTurbulence<TBuilder>(*this TBuilder, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence_1}

ビルダーに 'feTurbulence' 要素の構成を追加します。この要素はパーリンノイズを使用して画像を生成し、雲や大理石などのテクスチャ作成に役立ちます。

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    Action<SVGFETurbulenceElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | ‘feTurbulence’ 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeTurbulence<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, int?, double?, StitchTiles?, TurbulenceType?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence}

SVG ビルダーに 'feTurbulence' 要素を追加し、パーリンノイズを使用して雲や大理石などの乱流効果を作成します。

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> baseFrequency = null, int? numOctaves = null, 
    double? seed = null, StitchTiles? stitchTiles = default, TurbulenceType? type = default, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFETurbulenceElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | ‘feTurbulence’ 要素が追加される SVG ビルダーインスタンスです。 |
| baseFrequency | 乱流の基本周波数です。double または 2 つの double からなる ValueTuple を指定できます。省略可能なパラメーターです。 |
| numOctaves | 乱流のオクターブ数です。省略可能なパラメーターです。 |
| seed | 乱数生成器のシード番号です。省略可能なパラメーターです。 |
| stitchTiles | タイルが結合されているかどうかを示します。省略可能なパラメーターです。 |
| type | The type of turbulence (fractal noise or turbulence). Optional parameter. |
| in | 乱流効果を適用する入力画像です。文字列または FilterInput を指定できます。省略可能なパラメーターです。 |
| result | このフィルタプリミティブの結果識別子。オプションパラメータ。 |
| x | フィルタプリミティブサブ領域の x 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| y | フィルタプリミティブサブ領域の y 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| width | フィルタプリミティブサブ領域の幅です。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| height | フィルタプリミティブサブ領域の高さです。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| fill | 要素の塗りつぶし色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| stroke | 要素のストローク色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| id | フィルタプリミティブ要素の一意の識別子です。オプションパラメーター。 |
| extend | SVGFETurbulenceElementBuilder をさらに構成するためのオプションのアクションです。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StitchTiles](../../stitchtiles/)
* enum [TurbulenceType](../../turbulencetype/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
