---
title: "SVGBuilderExtensions.FontSize"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions FontSize メソッド。数値と特定の長さタイプを使用して SVG 要素の font-size 属性を設定します。"
type: docs
weight: 890
url: /ja/net/aspose.svg.builder/svgbuilderextensions/fontsize/
---
## FontSize<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontsize_1}

数値と特定の長さタイプを使用して SVG 要素の 'font-size' 属性を設定します。

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定するフォントサイズの値です。 |
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

## FontSize<TBuilder>(*this TBuilder, [FontSize](../../fontsize/)*) {#fontsize}

事前定義されたフォントサイズ値を使用して SVG 要素の 'font-size' 属性を設定します。

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, FontSize value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定する事前定義されたフォントサイズの値です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [FontSize](../../fontsize/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
