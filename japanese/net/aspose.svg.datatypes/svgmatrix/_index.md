---
title: "SVGMatrix クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.DataTypes.SVGMatrix class. 多くの SVG グラフィック操作は、a c e b d f の形の 2x3 行列を使用します。この行列は、行列演算の目的で 3x3 行列に拡張されると a c e b d f 0 0 1 となります。"
type: docs
weight: 2230
url: /ja/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

SVG の多くのグラフィック操作は、形式が [a c e] [b d f] の 2x3 行列を使用し、行列演算のために 3x3 行列に拡張すると [a c e] [b d f] [0 0 1] になります。

```csharp
public class SVGMatrix : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | 行列の A 成分です。 |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | 行列の B 成分です。 |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | 行列の C 成分です。 |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | 行列の D 成分です。 |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | 行列の E 成分です。 |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | 行列の F 成分です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(*SVGMatrix*) | 行列の乗算を実行します。この行列は別の行列で後置乗算され、結果として新しい行列が返されます。 |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(*float*) | 現在の行列に回転変換を後置乗算し、結果の行列を返します。 |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(*float*) | 現在の行列に均一スケール変換を後置乗算し、結果の行列を返します。 |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(*float, float*) | 現在の行列に非均一スケール変換を後置乗算し、結果の行列を返します。 |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(*float*) | 現在の行列に skewX 変換を後置乗算し、結果の行列を返します。 |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(*float*) | 現在の行列に skewY 変換を後置乗算し、結果の行列を返します。 |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | このインスタンスを表す String を返します。 |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(*float, float*) | 現在の行列に平行移動変換を後置乗算し、結果の行列を返します。 |

### 参照

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
