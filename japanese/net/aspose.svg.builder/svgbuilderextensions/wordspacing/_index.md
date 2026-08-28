---
title: "SVGBuilderExtensions.WordSpacing"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions の WordSpacing メソッド。単語間の間隔動作を指定する SVG 要素の word-spacing 属性を設定します。"
type: docs
weight: 2340
url: /ja/net/aspose.svg.builder/svgbuilderextensions/wordspacing/
---
## WordSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#wordspacing}

SVG 要素の 'word-spacing' 属性を設定し、単語間の間隔の動作を指定します。

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 事前定義された単語間隔の値です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## WordSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#wordspacing_1}

SVG 要素の 'word-spacing' 属性を設定し、カスタム値で単語間の間隔の動作を指定します。

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 単語間隔の値です。 |
| type | 間隔値の単位タイプです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
