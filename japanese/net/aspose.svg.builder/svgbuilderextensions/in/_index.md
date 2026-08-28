---
title: "SVGBuilderExtensions.In"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions In メソッド。SVG フィルタプリミティブの in 属性を設定します。"
type: docs
weight: 1040
url: /ja/net/aspose.svg.builder/svgbuilderextensions/in/
---
## In<TBuilder>(*this TBuilder, string*) {#in_1}

SVGフィルタプリミティブの 'in' 属性を設定します。

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 入力として使用するソースグラフィックまたはフィルタプリミティブの結果です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## In<TBuilder>(*this TBuilder, [FilterInput](../../filterinput/)*) {#in}

事前定義された入力ソースを使用して、SVGフィルタプリミティブの 'in' 属性を設定します。

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, FilterInput input)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| input | 事前定義された入力ソースです（例: SourceGraphic、SourceAlpha）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [FilterInput](../../filterinput/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
