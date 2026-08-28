---
title: "SVGBuilderExtensions.FontKerning"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions FontKerning メソッド。数値と特定の長さタイプを使用して、SVG 要素の font-kerning 属性を設定します。"
type: docs
weight: 880
url: /ja/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

数値と特定の長さタイプを使用して SVG 要素の 'font-kerning' 属性を設定します。

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定するフォントカーニング値です。 |
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

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

事前定義されたカーニング値を使用して SVG 要素の 'font-kerning' 属性を設定します。

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定する事前定義されたカーニング値です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
