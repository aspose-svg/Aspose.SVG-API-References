---
title: "SVGBuilderExtensions.AddFeConvolveMatrix"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddFeConvolveMatrix メソッド。ビルダーに feConvolveMatrix 要素の構成を追加します。この要素は行列畳み込みフィルター効果を適用します。"
type: docs
weight: 170
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addfeconvolvematrix/
---
## AddFeConvolveMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix_1}

ビルダーに 'feConvolveMatrix' 要素の構成を追加します。この要素は行列畳み込みフィルター効果を適用します。

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEConvolveMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 「feConvolveMatrix」要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeConvolveMatrix<TBuilder>(*this TBuilder, double[], double?, double?, int?, int?, EdgeMode?, bool?, OneOf&lt;int, (int, int)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix}

SVG ビルダーに 'feConvolveMatrix' 要素を追加し、行列畳み込みフィルター効果を適用します。

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    double[] kernelMatrix = null, double? divisor = null, double? bias = null, int? targetX = null, 
    int? targetY = null, EdgeMode? edgeMode = default, bool? preserveAlpha = null, 
    OneOf<int, (int, int)> order = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEConvolveMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | 「feConvolveMatrix」要素が追加されるSVGビルダーインスタンスです。 |
| kernelMatrix | 畳み込みに使用される値の行列です。オプションパラメーター。 |
| divisor | 畳み込みの除数です。オプションパラメーター。 |
| bias | 畳み込み結果に加えるバイアスです。オプションパラメーター。 |
| targetX | カーネル行列における対象ピクセルの x 座標です。オプション パラメーター。 |
| targetY | カーネル行列における対象ピクセルの y 座標です。オプション パラメーター。 |
| edgeMode | 畳み込みにおけるエッジピクセルの処理方法を定義します。オプション パラメーター。 |
| preserveAlpha | アルファチャンネルを保持するかどうかを示します。オプション パラメーター。 |
| order | カーネル行列の順序です。int または 2 つの int の ValueTuple を指定できます。オプション パラメーター。 |
| in | 畳み込み効果の入力です。文字列または FilterInput を指定できます。オプション パラメーター。 |
| result | このフィルタプリミティブの結果識別子。オプションパラメータ。 |
| x | フィルタプリミティブサブ領域の x 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| y | フィルタプリミティブサブ領域の y 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| width | フィルタプリミティブサブ領域の幅です。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| height | フィルタプリミティブサブ領域の高さです。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| fill | 要素の塗りつぶし色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| stroke | 要素のストローク色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| id | フィルタプリミティブ要素の一意の識別子です。オプションパラメーター。 |
| extend | SVGFEConvolveMatrixElementBuilder をさらに構成するためのオプション アクションです。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* enum [EdgeMode](../../edgemode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
