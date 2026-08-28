---
title: "SVGPoint クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.DataTypes.SVGPoint クラス。多くの SVG DOM インターフェイスは SVGPoint クラスのオブジェクトを参照します。SVGPoint は x と y の座標ペアです。行列演算で使用される場合、SVGPoint は x y 1 の形のベクトルとして扱われます。SVGRect オブジェクトが読み取り専用として指定されている場合、その属性のいずれかに代入しようとすると例外がスローされます。"
type: docs
weight: 2260
url: /ja/net/aspose.svg.datatypes/svgpoint/
---
## SVGPoint class

SVG DOM の多くのインターフェイスはクラス SVGPoint のオブジェクトを参照します。SVGPoint は (x, y) の座標ペアです。行列演算で使用される場合、SVGPoint は [x] [y] [1] の形のベクトルとして扱われます。SVGRect オブジェクトが読み取り専用に指定されている場合、その属性に代入しようとすると例外がスローされます。

```csharp
public class SVGPoint : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [X](../../aspose.svg.datatypes/svgpoint/x/) { get; set; } | X 座標です。 |
| [Y](../../aspose.svg.datatypes/svgpoint/y/) { get; set; } | Y 座標です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [MatrixTransform](../../aspose.svg.datatypes/svgpoint/matrixtransform/)(*[SVGMatrix](../svgmatrix/)*) | この SVGPoint オブジェクトに 2x3 行列変換を適用し、新しい変換後の SVGPoint オブジェクトを返します: newpoint = matrix * thispoint |
| override [ToString](../../aspose.svg.datatypes/svgpoint/tostring/)() | このインスタンスを表す String を返します。 |

### 参照

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
