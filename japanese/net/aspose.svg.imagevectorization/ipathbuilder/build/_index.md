---
title: "IPathBuilder.Build"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IPathBuilder Build メソッド。指定されたトレースを、最小限の直線およびベジエ曲線コマンドで正確に表現できる SVG パスセグメントに最適化します。"
type: docs
weight: 10
url: /ja/net/aspose.svg.imagevectorization/ipathbuilder/build/
---
## IPathBuilder.Build method

正確な表現のために、最小限の直線およびベジエ曲線コマンドを使用して、与えられたトレースを SVG パスセグメントに最適化します。

```csharp
public string Build(IEnumerable<PointF> trace)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| トレース | IEnumerable`1 | トレースを輪郭する点のシーケンスで、SVG パスに最適化されます。 |

### 戻り値

元のトレースを最小限の直線とベジエ曲線コマンドで効率的に近似した SVG パスセグメントを表す文字列です。

### 参照

* interface [IPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
