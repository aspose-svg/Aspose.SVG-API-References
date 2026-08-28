---
title: "SplinePathBuilder.Build"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SplinePathBuilder Build メソッド。Centripetal CatmullRom スプラインをベジェ曲線に変換して、点のシーケンスを通る滑らかなパスを構築します。このメソッドは各点で自然で滑らかな遷移を保証し、提供されたトレースに密接に従う SVG パスを生成します。"
type: docs
weight: 50
url: /ja/net/aspose.svg.imagevectorization/splinepathbuilder/build/
---
## SplinePathBuilder.Build method

遠心的 Catmull–Rom スプラインをベジェ曲線に変換して、点のシーケンスを通る滑らかなパスを構築します。このメソッドは各点で自然で滑らかな遷移を保証し、提供されたトレースに密着した SVG パスを作成します。

```csharp
public string Build(IEnumerable<PointF> trace)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| トレース | IEnumerable`1 | 滑らかなパスに補間される点のシーケンスです。 |

### 戻り値

ベジェ曲線コマンドと座標で構成され、Centripetal Catmull–Rom スプラインを近似する SVG パスデータを表す文字列です。

### 参照

* class [SplinePathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
