---
title: "ImageTraceSimplifier クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.ImageVectorization.ImageTraceSimplifier クラス。ImageTraceSimplifier クラスは、トレースポイントの系列で近似された曲線のポイント数を削減する役割を担います。"
type: docs
weight: 4190
url: /ja/net/aspose.svg.imagevectorization/imagetracesimplifier/
---
## ImageTraceSimplifier class

ImageTraceSimplifier クラスは、トレースポイントの系列で近似された曲線の点数を削減する役割を担います。

```csharp
public class ImageTraceSimplifier : IImageTraceSimplifier
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor)() | `ImageTraceSimplifier` クラスの新しいインスタンスを初期化します。 |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor_1)(*float*) | `ImageTraceSimplifier` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Tolerance](../../aspose.svg.imagevectorization/imagetracesimplifier/tolerance/) { get; set; } | 許容誤差の値は、トレースから点を除去できる最大誤差許容範囲を決定します。範囲は 0 から 4 まででなければなりません。この範囲の最小値または最大値を超える場合は、それぞれ最小値または最大値に合わせられます。デフォルト値は 0.3 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Simplify](../../aspose.svg.imagevectorization/imagetracesimplifier/simplify/)(*IEnumerable&lt;PointF&gt;*) | トレースポイントのリスト内の点の数を削減します。 |

### 参照

* interface [IImageTraceSimplifier](../iimagetracesimplifier/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
