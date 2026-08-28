---
title: "SVGBuilderExtensions.AddText"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddText メソッド。テキスト要素の構成をビルダーに追加します"
type: docs
weight: 530
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

ビルダーに 'text' 要素の構成を追加します。

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'text' 要素の構成アクション。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

SVG ビルダーに指定されたコンテンツと属性を持つ 'text' 要素を追加します。

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | チェーン可能な SVG 要素ビルダーの型です。 |
| ビルダー | 'text' 要素が追加されるビルダーインスタンス。 |
| content | 'text' 要素内に表示されるテキストコンテンツ。 |
| x | テキスト要素の x 座標。double 値または double と LengthType のタプルで指定できます。 |
| y | テキスト要素の y 座標。double 値または double と LengthType のタプルで指定できます。 |
| fontSize | テキストのフォントサイズ。double 値または double と LengthType のタプルで指定できます。 |
| fontStyle | テキストのフォントスタイル（例: normal、italic、oblique）。 |
| fontFamily | テキストのフォントファミリー（例: Arial、Verdana）。 |
| fontWeight | フォントの太さ（weight）（例: normal、bold）。 |
| fill | テキストの塗りつぶし色またはペイントスタイル。Color、Paint 列挙値、またはペイントサーバー ID のいずれかで指定できます。 |
| stroke | テキストのストロークカラーまたはペイントスタイルです。Color または Paint 列挙型の値、またはペイントサーバー ID を指定できます。 |
| id | テキスト要素の一意の識別子です。 |
| extend | テキスト要素ビルダーをさらに構成するためのオプションのアクションです。 |

### 戻り値

さらに追加や構成をチェーンできるビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
