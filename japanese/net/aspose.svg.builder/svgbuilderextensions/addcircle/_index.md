---
title: "SVGBuilderExtensions.AddCircle"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddCircle メソッド。ビルダーに円要素の構成を追加します。"
type: docs
weight: 70
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

ビルダーに 'circle' 要素の構成を追加します。

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 「circle」要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

指定された中心、半径、スタイルを持つ 'circle' 要素を SVG ビルダーに追加します。

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | 「circle」要素が追加される SVG ビルダーインスタンスです。 |
| cx | 円の中心の x 座標です。double 値または double と LengthType のタプルで指定できます。 |
| cy | 円の中心の y 座標です。double 値または double と LengthType のタプルで指定できます。 |
| r | 円の半径です。double 値または double と LengthType のタプルで指定できます。 |
| fill | 円の塗りつぶし色またはペイントスタイルです。Color、Paint 列挙型の値、またはペイントサーバー ID のいずれかで指定できます。省略可能なパラメーターです。 |
| stroke | 円の輪郭のストローク色またはペイントスタイルです。Color、Paint 列挙型の値、またはペイントサーバー ID のいずれかで指定できます。省略可能なパラメーターです。 |
| id | 円要素の一意の識別子です。省略可能なパラメーターです。 |
| extend | 円要素ビルダーをさらに構成するためのオプションのアクションです。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
