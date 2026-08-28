---
title: "SVGBuilderExtensions.Dx"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Dx メソッド。テキスト内の各文字の水平位置を調整するために dx 属性を設定します。"
type: docs
weight: 770
url: /ja/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

テキスト内の各文字の水平位置を調整するために、'dx' 属性を設定します。

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| type | 値の長さ単位のタイプです。 |
| values | 各文字の水平調整値です。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドはテキスト内の文字の水平間隔を細かく制御できます。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

テキストコンテンツに対して単一の水平調整値を設定します。

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 水平調整値。 |
| type | 値の長さ単位のタイプです。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドは単一の値で 'dx' 属性を設定し、テキストコンテンツの水平位置を調整します。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
