---
title: "ImageTraceSmoother クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.ImageVectorization.ImageTraceSmoother クラス。ImageTraceSimplifier クラスは、トレースポイントの系列で近似された曲線のポイント数を平滑化する役割を担います。このクラスは最近傍アプローチを実装します。"
type: docs
weight: 4200
url: /ja/net/aspose.svg.imagevectorization/imagetracesmoother/
---
## ImageTraceSmoother class

ImageTraceSimplifier クラスは、トレースポイントの系列で近似された曲線の点数を平滑化する役割を担います。このクラスは最近傍法を実装しています。

```csharp
public class ImageTraceSmoother : IImageTraceSmoother
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageTraceSmoother](imagetracesmoother/#constructor)() | `ImageTraceSmoother` クラスの新しいインスタンスを初期化します。 |
| [ImageTraceSmoother](imagetracesmoother/#constructor_1)(*int*) | `ImageTraceSmoother` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extent](../../aspose.svg.imagevectorization/imagetracesmoother/extent/) { get; set; } | クエリポイントで考慮される領域の範囲を取得または設定します。範囲は 1 から 20 まででなければなりません。これより高いまたは低い値は、範囲の最小値と最大値に合わせて調整されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Smooth](../../aspose.svg.imagevectorization/imagetracesmoother/smooth/)(*IEnumerable&lt;PointF&gt;*) | トレースを平滑化します。 |

### 参照

* interface [IImageTraceSmoother](../iimagetracesmoother/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
