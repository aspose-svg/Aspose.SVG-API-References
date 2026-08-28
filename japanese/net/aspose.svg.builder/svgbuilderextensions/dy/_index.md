---
title: "SVGBuilderExtensions.Dy"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Dy メソッド。テキストコンテンツの複数の垂直調整値を設定します。"
type: docs
weight: 780
url: /ja/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

テキストコンテンツの垂直調整値を複数設定します。

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| values | 垂直調整値の配列です。 |
| type | 値の長さ単位のタイプです。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドは複数の値で 'dy' 属性を設定し、各文字またはテキストセグメントごとに個別の垂直調整を可能にします。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

テキストコンテンツに対して単一の垂直調整値を設定します。

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 垂直調整値です。 |
| type | 値の長さ単位のタイプです。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドは単一の値で 'dy' 属性を設定し、テキストコンテンツの垂直位置を調整します。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
