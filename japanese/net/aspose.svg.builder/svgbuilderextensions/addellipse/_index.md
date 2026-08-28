---
title: "SVGBuilderExtensions.AddEllipse"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddEllipse メソッド。ビルダーに楕円要素の構成を追加します。"
type: docs
weight: 120
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

ビルダーに 'ellipse' 要素の構成を追加します。

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | ‘ellipse’ 要素の構成アクション。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

SVG ビルダーに 'ellipse' 要素を追加し、その中心、半径、およびスタイルを指定します。

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | ‘ellipse’ 要素が追加される SVG ビルダーインスタンス。 |
| cx | 楕円の中心の x 座標。double 値または double と LengthType のタプルで指定できます。 |
| cy | 楕円の中心の y 座標。double 値または double と LengthType のタプルで指定できます。 |
| rx | 楕円の x 半径。double 値または double と LengthType のタプルで指定できます。 |
| ry | 楕円の y 半径。double 値または double と LengthType のタプルで指定できます。 |
| fill | 楕円の塗りつぶし色またはペイントスタイル。Color、Paint 列挙型の値、またはペイントサーバー ID のいずれかで指定できます。省略可能なパラメーターです。 |
| stroke | 楕円のストローク色またはペイントスタイル。Color、Paint 列挙型の値、またはペイントサーバー ID のいずれかで指定できます。省略可能なパラメーターです。 |
| id | 楕円要素の一意識別子。省略可能なパラメーターです。 |
| extend | 楕円要素ビルダーをさらに構成するためのオプションのアクションです。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
