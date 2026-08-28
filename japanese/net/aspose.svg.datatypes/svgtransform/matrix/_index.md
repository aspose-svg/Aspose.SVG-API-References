---
title: "SVGTransform.Matrix"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGTransform Matrix プロパティ。この変換を表す行列です。行列オブジェクトはライブであり、SVGTransform オブジェクトに加えた変更は即座に行列オブジェクトに反映され、逆も同様です。行列オブジェクトが直接（SVGTransform インターフェイスのメソッドを使用せずに）変更された場合、SVGTransform のタイプは SVG_TRANSFORM_MATRIX に変わります。SVG_TRANSFORM_MATRIX の場合、行列はユーザーが提供した a, b, c, d, e, f の値を含みます。SVG_TRANSFORM_TRANSLATE の場合、e と f は平行移動量を表します（例: a=1, b=0, c=0, d=1）。SVG_TRANSFORM_SCALE の場合、a と d はスケール量を表します（例: b=0, c=0, e=0, f=0）。SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY の場合、a, b, c, d は指定されたスキューを生成する行列を表します（例: e=0, f=0）。SVG_TRANSFORM_ROTATE の場合、a, b, c, d, e, f が合わせて指定された回転を生成する行列を表します。回転が中心点 (0,0) 周りの場合、e と f は 0 になります。"
type: docs
weight: 20
url: /ja/net/aspose.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

この変換を表す行列です。行列オブジェクトはライブであり、SVGTransform オブジェクトへの変更は即座に行列オブジェクトに反映され、逆も同様です。行列オブジェクトが直接（つまり、SVGTransform インターフェイスのメソッドを使用せずに）変更された場合、SVGTransform のタイプは SVG_TRANSFORM_MATRIX に変わります。SVG_TRANSFORM_MATRIX の場合、行列はユーザーが提供した a、b、c、d、e、f の値を含みます。SVG_TRANSFORM_TRANSLATE の場合、e と f は平行移動量を表します (a=1、b=0、c=0、d=1)。SVG_TRANSFORM_SCALE の場合、a と d はスケール量を表します (b=0、c=0、e=0、f=0)。SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY の場合、a、b、c、d は指定されたスキューを生成する行列を表します (e=0、f=0)。SVG_TRANSFORM_ROTATE の場合、a、b、c、d、e、f が合わせて指定された回転を生成する行列を表します。回転の中心点が (0, 0) の場合、e と f は 0 になります。

```csharp
public SVGMatrix Matrix { get; }
```

### Property Value

この変換を表す行列です。

### 参照

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
