---
title: "SVGBuilderExtensions.AddFeFlood"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddFeFlood メソッド。ビルダーに feFlood 要素の構成を追加します。この要素は、指定された色でフィルタのサブ領域を塗りつぶします。"
type: docs
weight: 210
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addfeflood/
---
## AddFeFlood<TBuilder>(*this TBuilder, Action&lt;SVGFEFloodElementBuilder&gt;*) {#addfeflood}

ビルダーに 'feFlood' 要素の構成を追加します。この要素はフィルターのサブ領域を指定された色で塗りつぶします。

```csharp
public static TBuilder AddFeFlood<TBuilder>(this TBuilder builder, 
    Action<SVGFEFloodElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'feFlood' 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGFEFloodElementBuilder](../../svgfefloodelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeFlood<TBuilder>(*this TBuilder, Color?, double?, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEFloodElementBuilder&gt;*) {#addfeflood_1}

SVG ビルダーに 'feFlood' 要素を追加し、フィルターのサブ領域全体に均一なフラッドカラー効果を作成します。

```csharp
public static TBuilder AddFeFlood<TBuilder>(this TBuilder builder, Color? floodColor = default, 
    double? floodOpacity = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEFloodElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | 'feFlood' 要素が追加される SVG ビルダー インスタンスです。 |
| floodColor | 洪水効果に使用される色です。オプションパラメーター。 |
| floodOpacity | 洪水色の不透明度レベルです。オプションパラメーター。 |
| result | このフィルタプリミティブの結果識別子。オプションパラメータ。 |
| x | フィルタプリミティブサブ領域の x 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| y | フィルタプリミティブサブ領域の y 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| width | フィルタプリミティブサブ領域の幅です。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| height | フィルタプリミティブサブ領域の高さです。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| fill | 要素の塗りつぶし色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| stroke | 要素のストローク色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| id | フィルタプリミティブ要素の一意の識別子です。オプションパラメーター。 |
| extend | SVGFEFloodElementBuilder をさらに構成するためのオプションのアクションです。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEFloodElementBuilder](../../svgfefloodelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
