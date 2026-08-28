---
title: "SVGPathSeg クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Paths.SVGPathSeg クラス。SVGPathSeg インターフェイスは、パスデータ仕様内の単一コマンドに対応する基本インターフェイスです。"
type: docs
weight: 4560
url: /ja/net/aspose.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg インターフェイスは、パス データ仕様内の単一コマンドに対応する基本インターフェイスです。

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PathSegType](../../aspose.svg.paths/svgpathseg/pathsegtype/) { get; } | このインターフェイスで定義された定数のいずれかによって指定されるパス セグメントのタイプです。 |
| [PathSegTypeAsLetter](../../aspose.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | パスセグメントのタイプは、対応する1文字のコマンド名で指定されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_arc_abs/) | 「絶対 arcto」(A) パスデータコマンドに対応します。 |
| const [PATHSEG_ARC_REL](../../aspose.svg.paths/svgpathseg/pathseg_arc_rel/) | 「相対 arcto」(a) パスデータコマンドに対応します。 |
| const [PATHSEG_CLOSEPATH](../../aspose.svg.paths/svgpathseg/pathseg_closepath/) | 「closepath」(z) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | 「絶対 cubic Bézier curveto」(C) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | 「相対 cubic Bézier curveto」(c) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | 「絶対 smooth cubic curveto」(S) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | 「相対 smooth cubic curveto」(s) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | 「絶対 quadratic Bézier curveto」(Q) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | 「相対 quadratic Bézier curveto」(q) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | 「絶対 smooth quadratic curveto」(T) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | 「相対 smooth quadratic curveto」(t) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_abs/) | 「絶対 lineto」(L) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | 「絶対 horizontal lineto」(H) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | 「相対 horizontal lineto」(h) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_rel/) | 「相対 lineto」(l) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | 「絶対垂直線分」(V) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | 「相対垂直線分」(v) パスデータコマンドに対応します。 |
| const [PATHSEG_MOVETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_moveto_abs/) | 「絶対移動」(M) パスデータコマンドに対応します。 |
| const [PATHSEG_MOVETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_moveto_rel/) | 「相対移動」(m) パスデータコマンドに対応します。 |
| const [PATHSEG_UNKNOWN](../../aspose.svg.paths/svgpathseg/pathseg_unknown/) | 単位タイプは事前定義されたタイプのいずれでもありません。このタイプの新しい値を定義しようとしたり、既存の値をこのタイプに切り替えようとすることは無効です。 |

### 参照

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
