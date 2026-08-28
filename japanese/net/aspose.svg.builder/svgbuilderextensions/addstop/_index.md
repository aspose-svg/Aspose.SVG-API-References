---
title: "SVGBuilderExtensions.AddStop"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddStop メソッド。グラデーションストップを定義するためにビルダーに stop 要素の構成を追加します。"
type: docs
weight: 480
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addstop/
---
## AddStop<TBuilder>(*this TBuilder, Action&lt;SVGStopElementBuilder&gt;*) {#addstop}

ビルダーにグラデーションストップを定義するための 'stop' 要素の構成を追加します。

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, 
    Action<SVGStopElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'stop' 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddStop<TBuilder>(*this TBuilder, Color?, double?, OneOf&lt;double, (double, StopUnitType)&gt;, string, Action&lt;SVGStopElementBuilder&gt;*) {#addstop_1}

SVG ビルダーのグラデーションに 'stop' 要素を追加し、特定のオフセットで色と不透明度を指定します。

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, Color? stopColor = default, 
    double? stopOpacity = null, OneOf<double, (double, StopUnitType)> offset = null, 
    string id = null, Action<SVGStopElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | 流暢な API 使用を容易にする SVG 要素ビルダーの型。 |
| ビルダー | 'stop' 要素が追加される SVG ビルダーインスタンスです。 |
| stopColor | ストップ時の色です。省略可能なパラメーター。 |
| stopOpacity | ストップ時の不透明度です。省略可能なパラメーター。 |
| オフセット | グラデーション内のストップのオフセットです。double または StopUnitType を含む ValueTuple を指定できます。省略可能なパラメーター。 |
| id | ストップ要素の一意の識別子です。省略可能なパラメーター。 |
| extend | ストップ要素ビルダーをさらに構成するためのオプションのアクションです。 |

### 戻り値

メソッドチェーンを可能にするビルダーインスタンスです。

### 参照

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StopUnitType](../../stopunittype/)
* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
