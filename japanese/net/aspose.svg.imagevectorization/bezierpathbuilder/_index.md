---
title: "BezierPathBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.ImageVectorization.BezierPathBuilder クラス。BezierPathBuilder クラスは、与えられた点の集合からベジェパスを構築する役割を担います。ベジェ曲線で点のトレースを近似し、セグメント数を最適化して元のトレースにできるだけ近づけつつ、複雑さを最小限に抑えます"
type: docs
weight: 4150
url: /ja/net/aspose.svg.imagevectorization/bezierpathbuilder/
---
## BezierPathBuilder class

`BezierPathBuilder` クラスは、与えられた点の集合からベジェパスを構築する役割を担います。ベジェ曲線で点のトレースを近似し、セグメント数を最適化して元のトレースにできるだけ近づけつつ、複雑さを最小限に抑えます。

```csharp
public class BezierPathBuilder : IPathBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [BezierPathBuilder](bezierpathbuilder/)() | `BezierPathBuilder` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ErrorThreshold](../../aspose.svg.imagevectorization/bezierpathbuilder/errorthreshold/) { get; set; } | エラースレッショルドを取得または設定します。このパラメータは点とフィットした曲線との最大偏差を定義します。デフォルトは 30 です。 |
| [MaxIterations](../../aspose.svg.imagevectorization/bezierpathbuilder/maxiterations/) { get; set; } | エラー閾値を取得または設定します。このパラメーターは最小二乗近似法の反復回数を定義します。デフォルトは30です。 |
| [TraceSmoother](../../aspose.svg.imagevectorization/bezierpathbuilder/tracesmoother/) { get; set; } | トレース平滑化ツールを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/bezierpathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | トレースポイントのシーケンスから最適化されたベジエパスを構築します。このメソッドは、直線と曲線セグメントの組み合わせを使用して、与えられたトレースをベジエ曲線で近似します。元のトレースに密接にフィットさせながら、セグメント数を最小限に抑えることを目的としています。 |

### 参照

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
