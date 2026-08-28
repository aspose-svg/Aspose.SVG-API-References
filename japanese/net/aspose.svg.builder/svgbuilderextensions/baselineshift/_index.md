---
title: "SVGBuilderExtensions.BaselineShift"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions BaselineShift メソッド。事前定義された値を使用して SVG 要素の baseline-shift 属性を設定します。"
type: docs
weight: 600
url: /ja/net/aspose.svg.builder/svgbuilderextensions/baselineshift/
---
## BaselineShift<TBuilder>(*this TBuilder, [BaseLineShift](../../baselineshift/)*) {#baselineshift}

事前定義された値を使用して、SVG 要素の 'baseline-shift' 属性を設定します。

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, BaseLineShift value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定する baseline shift の値です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [BaseLineShift](../../baselineshift/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## BaselineShift<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#baselineshift_1}

数値を使用して、SVG 要素の 'baseline-shift' 属性を設定します。

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | baseline shift の数値です。 |
| type | 長さ単位のタイプです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
