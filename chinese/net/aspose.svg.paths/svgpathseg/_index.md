---
title: "SVGPathSeg 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Paths.SVGPathSeg 类。SVGPathSeg 接口是一个基础接口，对应路径数据规范中的单个命令。"
type: docs
weight: 4560
url: /zh/net/aspose.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg 接口是对应于路径数据规范中单个命令的基础接口。

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [PathSegType](../../aspose.svg.paths/svgpathseg/pathsegtype/) { get; } | 路径段的类型，由此接口上定义的常量之一指定。 |
| [PathSegTypeAsLetter](../../aspose.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | 路径段的类型，由相应的单字符命令名称指定。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_arc_abs/) | 对应一个“绝对 arcto”(A) 路径数据命令。 |
| const [PATHSEG_ARC_REL](../../aspose.svg.paths/svgpathseg/pathseg_arc_rel/) | 对应一个“相对 arcto”(a) 路径数据命令。 |
| const [PATHSEG_CLOSEPATH](../../aspose.svg.paths/svgpathseg/pathseg_closepath/) | 对应一个“closepath”(z) 路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | 对应一个“绝对 cubic Bézier curveto”(C) 路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | 对应一个“相对 cubic Bézier curveto”(c) 路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | 对应一个“绝对 smooth cubic curveto”(S) 路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | 对应一个“相对 smooth cubic curveto”(s) 路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | 对应一个“绝对 quadratic Bézier curveto”(Q) 路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | 对应一个“相对 quadratic Bézier curveto”(q) 路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | 对应一个“绝对 smooth quadratic curveto”(T) 路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | 对应一个“相对 smooth quadratic curveto”(t) 路径数据命令。 |
| const [PATHSEG_LINETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_abs/) | 对应一个“绝对 lineto”(L) 路径数据命令。 |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | 对应一个“绝对 horizontal lineto”(H) 路径数据命令。 |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | 对应一个“相对 horizontal lineto”(h) 路径数据命令。 |
| const [PATHSEG_LINETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_rel/) | 对应一个“相对 lineto”(l) 路径数据命令。 |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | 对应一个“绝对 vertical lineto”(V) 路径数据命令。 |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | 对应一个“相对 vertical lineto”(v) 路径数据命令。 |
| const [PATHSEG_MOVETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_moveto_abs/) | 对应一个“绝对 moveto”(M) 路径数据命令。 |
| const [PATHSEG_MOVETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_moveto_rel/) | 对应一个“相对 moveto”(m) 路径数据命令。 |
| const [PATHSEG_UNKNOWN](../../aspose.svg.paths/svgpathseg/pathseg_unknown/) | 该单位类型不是预定义类型之一。尝试定义此类型的新值或尝试将现有值切换为此类型都是无效的。 |

### 另请参阅

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
