---
title: "SVGPathSeg Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Paths.SVGPathSeg Klasse. Das SVGPathSeg Interface ist ein Basis‑Interface, das einem einzelnen Befehl innerhalb einer Pfaddaten‑Spezifikation entspricht"
type: docs
weight: 4560
url: /de/net/aspose.svg.paths/svgpathseg/
---
## SVGPathSeg class

Das SVGPathSeg-Interface ist eine Basisschnittstelle, die einem einzelnen Befehl innerhalb einer Pfaddaten-Spezifikation entspricht.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [PathSegType](../../aspose.svg.paths/svgpathseg/pathsegtype/) { get; } | Der Typ des Pfadsegments, wie durch eine der auf diesem Interface definierten Konstanten angegeben. |
| [PathSegTypeAsLetter](../../aspose.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | Der Typ des Pfadsegments, angegeben durch den entsprechenden ein‑Buchstaben‑Befehlsnamen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_arc_abs/) | Entspricht einem "absoluten arcto" (A) Pfaddatenbefehl. |
| const [PATHSEG_ARC_REL](../../aspose.svg.paths/svgpathseg/pathseg_arc_rel/) | Entspricht einem "relativen arcto" (a) Pfaddatenbefehl. |
| const [PATHSEG_CLOSEPATH](../../aspose.svg.paths/svgpathseg/pathseg_closepath/) | Entspricht einem "closepath" (z) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Entspricht einem "absoluten kubischen Bézier‑Curveto" (C) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Entspricht einem "relativen kubischen Bézier-Curveto" (c) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Entspricht einem "absoluten glatten kubischen Curveto" (S) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Entspricht einem "relativen glatten kubischen Curveto" (s) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Entspricht einem "absoluten quadratischen Bézier-Curveto" (Q) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Entspricht einem "relativen quadratischen Bézier-Curveto" (q) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Entspricht einem "absoluten glatten quadratischen Curveto" (T) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Entspricht einem "relativen glatten quadratischen Curveto" (t) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_abs/) | Entspricht einem "absoluten Lineto" (L) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Entspricht einem "absoluten horizontalen Lineto" (H) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Entspricht einem "relativen horizontalen Lineto" (h) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_rel/) | Entspricht einem "relativen Lineto" (l) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Entspricht einem "absoluten vertikalen Lineto" (V) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Entspricht einem "relativen vertikalen Lineto" (v) Pfaddatenbefehl. |
| const [PATHSEG_MOVETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_moveto_abs/) | Entspricht einem "absoluten Moveto" (M) Pfaddatenbefehl. |
| const [PATHSEG_MOVETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_moveto_rel/) | Entspricht einem "relativen Moveto" (m) Pfaddatenbefehl. |
| const [PATHSEG_UNKNOWN](../../aspose.svg.paths/svgpathseg/pathseg_unknown/) | Der Einheitstyp ist keiner der vordefinierten Typen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |

### Siehe auch

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
