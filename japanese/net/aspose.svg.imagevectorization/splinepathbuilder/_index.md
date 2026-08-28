---
title: "SplinePathBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.ImageVectorization.SplinePathBuilder クラス。SplinePathBuilder クラスは、遠心的 CatmullRom スプラインをベジェ曲線に変換して滑らかなパスを構築するように設計されています。点の集合を滑らかに補間するパスを生成するメソッドを提供し、点への忠実度と曲線の滑らかさのバランスを取ります"
type: docs
weight: 4230
url: /ja/net/aspose.svg.imagevectorization/splinepathbuilder/
---
## SplinePathBuilder class

`SplinePathBuilder` クラスは、遠心的 Catmull–Rom スプラインをベジェ曲線に変換して滑らかなパスを構築するように設計されています。点の集合を滑らかに補間するパスを生成するメソッドを提供し、点への忠実度と曲線の滑らかさのバランスを取ります。

```csharp
public class SplinePathBuilder : IPathBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SplinePathBuilder](splinepathbuilder/#constructor)() | `SplinePathBuilder` クラスの新しいインスタンスを初期化します。 |
| [SplinePathBuilder](splinepathbuilder/#constructor_2)(*float*) | `SplinePathBuilder` クラスの新しいインスタンスを初期化します。 |
| [SplinePathBuilder](splinepathbuilder/#constructor_1)(*[IImageTraceSmoother](../iimagetracesmoother/), [IImageTraceSimplifier](../iimagetracesimplifier/), float*) | `SplinePathBuilder` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/splinepathbuilder/tension/) { get; set; } | テンションの値は、（補間された）制御点で曲線がどれだけ急激に曲がるかに影響します。範囲は 0 から 1 まででなければなりません。この範囲を超える値は、最小または最大値に合わせて調整されます。 |
| [TraceSimplifier](../../aspose.svg.imagevectorization/splinepathbuilder/tracesimplifier/) { get; set; } | トレース簡略化ツールを取得または設定します。 |
| [TraceSmoother](../../aspose.svg.imagevectorization/splinepathbuilder/tracesmoother/) { get; set; } | トレース平滑化ツールを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/splinepathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | 遠心的 Catmull–Rom スプラインをベジェ曲線に変換して、点のシーケンスを通る滑らかなパスを構築します。このメソッドは各点で自然で滑らかな遷移を保証し、提供されたトレースに密着した SVG パスを作成します。 |

### 参照

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
