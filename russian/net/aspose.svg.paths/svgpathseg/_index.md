---
title: "Класс SVGPathSeg"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Paths.SVGPathSeg class. Интерфейс SVGPathSeg является базовым интерфейсом, который соответствует отдельной команде в спецификации данных пути."
type: docs
weight: 4560
url: /ru/net/aspose.svg.paths/svgpathseg/
---
## SVGPathSeg class

Интерфейс SVGPathSeg является базовым интерфейсом, соответствующим одной команде в спецификации данных пути.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [PathSegType](../../aspose.svg.paths/svgpathseg/pathsegtype/) { get; } | Тип сегмента пути, указанный одной из констант, определённых в этом интерфейсе. |
| [PathSegTypeAsLetter](../../aspose.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | Тип сегмента пути, указанный соответствующим односимвольным именем команды. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |

## Поля

| Имя | Описание |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_arc_abs/) | Соответствует команде данных пути "absolute arcto" (A). |
| const [PATHSEG_ARC_REL](../../aspose.svg.paths/svgpathseg/pathseg_arc_rel/) | Соответствует команде данных пути "relative arcto" (a). |
| const [PATHSEG_CLOSEPATH](../../aspose.svg.paths/svgpathseg/pathseg_closepath/) | Соответствует команде данных пути "closepath" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Соответствует команде данных пути "absolute cubic Bézier curveto" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Соответствует команде данных пути "relative cubic Bézier curveto" (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Соответствует команде данных пути "absolute smooth cubic curveto" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Соответствует команде данных пути "relative smooth cubic curveto" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Соответствует команде данных пути "absolute quadratic Bézier curveto" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Соответствует команде данных пути "relative quadratic Bézier curveto" (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Соответствует команде данных пути "absolute smooth quadratic curveto" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Соответствует команде данных пути "relative smooth quadratic curveto" (t). |
| const [PATHSEG_LINETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_abs/) | Соответствует команде данных пути "absolute lineto" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Соответствует команде данных пути " absolute horizontal lineto" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Соответствует команде данных пути "relative horizontal lineto" (h). |
| const [PATHSEG_LINETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_rel/) | Соответствует команде данных пути "relative lineto" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Соответствует команде данных пути "absolute vertical lineto" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Соответствует команде данных пути "relative vertical lineto" (v). |
| const [PATHSEG_MOVETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_moveto_abs/) | Соответствует команде данных пути "absolute moveto" (M). |
| const [PATHSEG_MOVETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_moveto_rel/) | Соответствует команде данных пути "relative moveto" (m). |
| const [PATHSEG_UNKNOWN](../../aspose.svg.paths/svgpathseg/pathseg_unknown/) | Тип единицы не является одним из предопределённых типов. Недопустимо пытаться определить новое значение этого типа или пытаться переключить существующее значение на этот тип. |

### См. также

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
