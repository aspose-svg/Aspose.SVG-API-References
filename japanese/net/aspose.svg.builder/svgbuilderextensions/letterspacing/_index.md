---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions LetterSpacing メソッド。数値と特定の長さタイプを使用して SVG 要素の letter-spacing 属性を設定します。"
type: docs
weight: 1100
url: /ja/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

数値と特定の長さタイプを使用して、SVG要素の 'letter-spacing' 属性を設定します。

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定する文字間隔の値。 |
| type | 長さのタイプ（例: px、em）です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

事前定義された間隔値を使用して、SVG要素の 'letter-spacing' 属性を設定します。

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定する事前定義された間隔の値。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
