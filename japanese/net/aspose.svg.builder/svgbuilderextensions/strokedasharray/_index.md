---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions StrokeDashArray メソッド。ストロークを描画するために使用されるダッシュとギャップのパターンを定義する SVG 要素の stroke-dasharray 属性を設定します。"
type: docs
weight: 2090
url: /ja/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

SVG 要素の 'stroke-dasharray' 属性を設定し、ストロークを描画する際に使用されるダッシュとギャップのパターンを定義します。

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| dashArray | ダッシュ長さの配列です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

事前定義されたダッシュパターンを使用して、SVG 要素の 'stroke-dasharray' 属性を設定します。

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定するダッシュパターンです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
