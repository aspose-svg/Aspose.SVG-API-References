---
title: "SVGBuilderExtensions.AddFeTile"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddFeTile メソッド。builder に feTile 要素の構成を追加します。この要素は入力画像の繰り返しタイルパターンで矩形を埋めます"
type: docs
weight: 280
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addfetile/
---
## AddFeTile<TBuilder>(*this TBuilder, Action&lt;SVGFETileElementBuilder&gt;*) {#addfetile_1}

ビルダーに 'feTile' 要素の構成を追加します。この要素は入力画像の繰り返しタイルパターンで矩形を埋めます。

```csharp
public static TBuilder AddFeTile<TBuilder>(this TBuilder builder, 
    Action<SVGFETileElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'feTile' 要素の構成アクション。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGFETileElementBuilder](../../svgfetileelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeTile<TBuilder>(*this TBuilder, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFETileElementBuilder&gt;*) {#addfetile}

SVG ビルダーに 'feTile' 要素を追加し、入力画像を複製してタイルパターンを作成します。

```csharp
public static TBuilder AddFeTile<TBuilder>(this TBuilder builder, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFETileElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | 'feTile' 要素が追加される SVG ビルダーインスタンス。 |
| in | タイルに複製される入力画像。文字列または FilterInput にできます。省略可能なパラメーターです。 |
| result | このフィルタプリミティブの結果識別子。オプションパラメータ。 |
| x | フィルタプリミティブサブ領域の x 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| y | フィルタプリミティブサブ領域の y 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| width | フィルタプリミティブサブ領域の幅です。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| height | フィルタプリミティブサブ領域の高さです。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| fill | 要素の塗りつぶし色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| stroke | 要素のストローク色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| id | フィルタプリミティブ要素の一意の識別子です。オプションパラメーター。 |
| extend | SVGFETileElementBuilder をさらに構成するためのオプションのアクション。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFETileElementBuilder](../../svgfetileelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
