---
title: "فئة SVGPathSeg"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Paths.SVGPathSeg. الواجهة SVGPathSeg هي واجهة أساسية تتطابق مع أمر واحد داخل مواصفة بيانات المسار"
type: docs
weight: 4560
url: /ar/net/aspose.svg.paths/svgpathseg/
---
## SVGPathSeg class

واجهة SVGPathSeg هي واجهة أساسية تتطابق مع أمر واحد داخل مواصفة بيانات المسار.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PathSegType](../../aspose.svg.paths/svgpathseg/pathsegtype/) { get; } | نوع مقطع المسار كما هو محدد بأحد الثوابت المعرفة في هذه الواجهة. |
| [PathSegTypeAsLetter](../../aspose.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | نوع مقطع المسار، المحدد باسم الأمر المكوّن من حرف واحد المقابل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و- اختياريًا - المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_arc_abs/) | يتطابق مع أمر بيانات مسار "arcto" المطلق (A). |
| const [PATHSEG_ARC_REL](../../aspose.svg.paths/svgpathseg/pathseg_arc_rel/) | يتطابق مع أمر بيانات مسار "arcto" النسبي (a). |
| const [PATHSEG_CLOSEPATH](../../aspose.svg.paths/svgpathseg/pathseg_closepath/) | يتطابق مع أمر بيانات مسار "closepath" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | يتطابق مع أمر بيانات مسار "cubic Bézier curveto" المطلق (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | يتطابق مع أمر بيانات مسار "cubic Bézier curveto" النسبي (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | يتطابق مع أمر بيانات مسار "smooth cubic curveto" المطلق (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | يتطابق مع أمر بيانات مسار "smooth cubic curveto" النسبي (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | يتطابق مع أمر بيانات مسار "quadratic Bézier curveto" المطلق (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | يتطابق مع أمر بيانات مسار "quadratic Bézier curveto" النسبي (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | يتطابق مع أمر بيانات مسار "smooth quadratic curveto" المطلق (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | يتطابق مع أمر بيانات مسار "smooth quadratic curveto" النسبي (t). |
| const [PATHSEG_LINETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_abs/) | يتطابق مع أمر بيانات مسار "lineto" المطلق (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | يتطابق مع أمر بيانات مسار "horizontal lineto" المطلق (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | يتطابق مع أمر بيانات مسار "horizontal lineto" النسبي (h). |
| const [PATHSEG_LINETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_rel/) | يتطابق مع أمر بيانات مسار "lineto" النسبي (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | يتطابق مع أمر بيانات مسار "vertical lineto" المطلق (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | يتطابق مع أمر بيانات مسار "vertical lineto" النسبي (v). |
| const [PATHSEG_MOVETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_moveto_abs/) | يتطابق مع أمر بيانات مسار "moveto" المطلق (M). |
| const [PATHSEG_MOVETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_moveto_rel/) | يتطابق مع أمر بيانات مسار "moveto" النسبي (m). |
| const [PATHSEG_UNKNOWN](../../aspose.svg.paths/svgpathseg/pathseg_unknown/) | نوع الوحدة ليس أحد الأنواع المعرفة مسبقًا. من غير الصالح محاولة تعريف قيمة جديدة لهذا النوع أو محاولة تحويل قيمة موجودة إلى هذا النوع. |

### انظر أيضًا

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
