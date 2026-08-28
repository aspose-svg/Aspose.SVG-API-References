---
title: "BezierPathBuilder.Build"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "BezierPathBuilder Build メソッド。トレースポイントのシーケンスから最適化されたベジェパスを構築します。このメソッドは、直線と曲線セグメントの組み合わせを使用して、与えられたトレースをベジェ曲線で近似します。セグメント数を最小限に抑えつつ、パスが元のトレースに密接に適合するようにします。"
type: docs
weight: 50
url: /ja/net/aspose.svg.imagevectorization/bezierpathbuilder/build/
---
## BezierPathBuilder.Build method

トレースポイントのシーケンスから最適化されたベジエパスを構築します。このメソッドは、直線と曲線セグメントの組み合わせを使用して、与えられたトレースをベジエ曲線で近似します。元のトレースに密接にフィットさせながら、セグメント数を最小限に抑えることを目的としています。

```csharp
public string Build(IEnumerable<PointF> trace)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| トレース | IEnumerable`1 | 近似対象となるトレースを定義する点のシーケンスです。 |

### 戻り値

SVG パスデータを表す文字列です。このデータは、ベジエパスを定義する一連のコマンドと座標で構成され、入力トレースを最小限の複雑さで正確に近似します。

### 参照

* class [BezierPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
