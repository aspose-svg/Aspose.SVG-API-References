---
title: "SVGTransform クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.DataTypes.SVGTransform クラス。SVGTransform は SVGTransformList 内のコンポーネント変換の一つのインターフェイスであり、SVGTransform オブジェクトは変換属性指定内の単一コンポーネント（例：scale や matrix）に対応します"
type: docs
weight: 2310
url: /ja/net/aspose.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform は SVGTransformList 内の構成変換の一つのインターフェイスであり、SVGTransform オブジェクトは ‘transform’ 属性指定内の単一コンポーネント（例：'scale(…)' や 'matrix(…)') に対応します。

```csharp
public class SVGTransform : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.svg.datatypes/svgtransform/angle/) { get; } | SVG_TRANSFORM_ROTATE、SVG_TRANSFORM_SKEWX、SVG_TRANSFORM_SKEWY 用の便利な属性です。指定された角度を保持します。SVG_TRANSFORM_MATRIX、SVG_TRANSFORM_TRANSLATE、SVG_TRANSFORM_SCALE の場合、角度は 0 になります。 |
| [Matrix](../../aspose.svg.datatypes/svgtransform/matrix/) { get; } | この変換を表す行列です。行列オブジェクトはライブであり、SVGTransform オブジェクトへの変更は即座に行列オブジェクトに反映され、逆も同様です。行列オブジェクトが直接（つまり、SVGTransform インターフェイスのメソッドを使用せずに）変更された場合、SVGTransform のタイプは SVG_TRANSFORM_MATRIX に変わります。SVG_TRANSFORM_MATRIX の場合、行列はユーザーが提供した a、b、c、d、e、f の値を含みます。SVG_TRANSFORM_TRANSLATE の場合、e と f は平行移動量を表します (a=1、b=0、c=0、d=1)。SVG_TRANSFORM_SCALE の場合、a と d はスケール量を表します (b=0、c=0、e=0、f=0)。SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY の場合、a、b、c、d は指定されたスキューを生成する行列を表します (e=0、f=0)。SVG_TRANSFORM_ROTATE の場合、a、b、c、d、e、f が合わせて指定された回転を生成する行列を表します。回転の中心点が (0, 0) の場合、e と f は 0 になります。 |
| [Type](../../aspose.svg.datatypes/svgtransform/type/) { get; } | このインターフェイスで定義された SVG_TRANSFORM_* 定数のいずれかによって指定された値のタイプです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [SetMatrix](../../aspose.svg.datatypes/svgtransform/setmatrix/)(*[SVGMatrix](../svgmatrix/)*) | 変換タイプを SVG_TRANSFORM_MATRIX に設定し、parameter matrix で新しい変換を定義します。parameter matrix の値はコピーされ、matrix パラメータは SVGTransform::matrix を置き換えません。 |
| [SetRotate](../../aspose.svg.datatypes/svgtransform/setrotate/)(*float, float, float*) | 変換タイプを SVG_TRANSFORM_ROTATE に設定し、parameter angle で回転角度を、パラメータ cx と cy でオプションの回転中心を定義します。 |
| [SetScale](../../aspose.svg.datatypes/svgtransform/setscale/)(*float, float*) | 変換タイプを SVG_TRANSFORM_SCALE に設定し、パラメータ sx と sy でスケール量を定義します。 |
| [SetSkewX](../../aspose.svg.datatypes/svgtransform/setskewx/)(*float*) | 変換タイプを SVG_TRANSFORM_SKEWX に設定し、parameter angle でスキュー量を定義します。 |
| [SetSkewY](../../aspose.svg.datatypes/svgtransform/setskewy/)(*float*) | 変換タイプを SVG_TRANSFORM_SKEWY に設定し、parameter angle でスキュー量を定義します。 |
| [SetTranslate](../../aspose.svg.datatypes/svgtransform/settranslate/)(*float, float*) | 変換タイプを SVG_TRANSFORM_TRANSLATE に設定し、パラメータ tx と ty で平行移動量を定義します。 |
| override [ToString](../../aspose.svg.datatypes/svgtransform/tostring/)() | このインスタンスを表す String を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.svg.datatypes/svgtransform/svg_transform_matrix/) | 「matrix(…)」変換。 |
| const [SVG_TRANSFORM_ROTATE](../../aspose.svg.datatypes/svgtransform/svg_transform_rotate/) | 「rotate(…)」変換。 |
| const [SVG_TRANSFORM_SCALE](../../aspose.svg.datatypes/svgtransform/svg_transform_scale/) | 「scale(…)」変換。 |
| const [SVG_TRANSFORM_SKEWX](../../aspose.svg.datatypes/svgtransform/svg_transform_skewx/) | 「skewX(…)」変換。 |
| const [SVG_TRANSFORM_SKEWY](../../aspose.svg.datatypes/svgtransform/svg_transform_skewy/) | 'skewY(…)’ 変換。 |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.svg.datatypes/svgtransform/svg_transform_translate/) | 'translate(…)’ 変換。 |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.svg.datatypes/svgtransform/svg_transform_unknown/) | 単位タイプは事前定義されたタイプのいずれでもありません。このタイプの新しい値を定義しようとしたり、既存の値をこのタイプに切り替えようとすることは無効です。 |

### 参照

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
