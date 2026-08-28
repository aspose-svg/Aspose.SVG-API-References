---
title: "SVGGeometryElement.Combine"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGGeometryElement Combine メソッド。このジオメトリを別の SVG ジオメトリとブール演算で結合し、結果を含む新しいパス要素を返します。"
type: docs
weight: 20
url: /ja/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

このジオメトリを別の SVG ジオメトリとブール演算で結合し、結果を含む新しい `<path>` 要素を返します。

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | 結合対象となるもう一方のジオメトリです。同じドキュメント内にある必要があります。 |
| op | BooleanPathOp | 適用するブール演算子: Union (A UNION B)、Difference (A - B)、Intersection (A INTERSECT B)、または Exclusion (XOR)。 |

### 戻り値

結果をルート `<svg>` のユーザー空間（CSS px）でエンコードした `d` 属性を持つ新しい [`SVGPathElement`](../../svgpathelement/) です。この要素は DOM に追加されません。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *geometryElement* が null の場合にスローされます。 |
| InvalidOperationException | この要素に所有ドキュメントがない場合にスローされます。 |
| NotSupportedException | ブールパス操作が利用できない場合にスローされます。この機能は SkiaSharp バックエンドが必要です（Aspose.SVG.Drawing.SkiaSharp パッケージをインストールしてください）。 |

### 参照

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
