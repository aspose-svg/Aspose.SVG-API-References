---
title: "SVGBuilderExtensions.AddFeImage"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddFeImage メソッド。ビルダーに feImage 要素の構成を追加します。この要素は外部画像を取得し、フィルタ パイプラインに含めます。"
type: docs
weight: 230
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addfeimage/
---
## AddFeImage<TBuilder>(*this TBuilder, Action&lt;SVGFEImageElementBuilder&gt;*) {#addfeimage}

ビルダーに 'feImage' 要素の構成を追加します。この要素は外部画像を取得し、フィルターパイプラインに組み込みます。

```csharp
public static TBuilder AddFeImage<TBuilder>(this TBuilder builder, 
    Action<SVGFEImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'feImage' 要素の構成アクション。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGFEImageElementBuilder](../../svgfeimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeImage<TBuilder>(*this TBuilder, string, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEImageElementBuilder&gt;*) {#addfeimage_1}

SVG ビルダーに 'feImage' 要素を追加し、外部画像をフィルター効果に組み込みます。

```csharp
public static TBuilder AddFeImage<TBuilder>(this TBuilder builder, string href = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | 'feImage' 要素が追加される SVG ビルダー インスタンス。 |
| href | 外部画像への URL または参照。省略可能なパラメーター。 |
| result | このフィルタプリミティブの結果識別子。オプションパラメータ。 |
| x | フィルタプリミティブサブ領域の x 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| y | フィルタプリミティブサブ領域の y 座標。double または LengthType を持つ ValueTuple を指定できます。オプションパラメータ。 |
| width | フィルタプリミティブサブ領域の幅です。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| height | フィルタプリミティブサブ領域の高さです。double または LengthType を持つ ValueTuple にすることができます。オプションパラメーター。 |
| fill | 要素の塗りつぶし色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| stroke | 要素のストローク色、ペイント、またはペイントサーバー ID です。オプションパラメーター。 |
| id | フィルタプリミティブ要素の一意の識別子です。オプションパラメーター。 |
| extend | SVGFEImageElementBuilder をさらに構成するためのオプション アクション。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEImageElementBuilder](../../svgfeimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
