---
title: "SVGBuilderExtensions.Points"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Points メソッド。double 配列を使用して SVG 要素の points 属性を設定します。"
type: docs
weight: 1910
url: /ja/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

配列の double を使用して SVG 要素の 'points' 属性を設定します。

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| points | ポイントを表す double 配列です（偶数である必要があります）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | ポイントの数が奇数の場合に例外がスローされます。 |

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

PointF オブジェクトの配列を使用して SVG 要素の 'points' 属性を設定します。

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| points | ポイントを表す PointF オブジェクトの配列です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
