---
title: "Κλάση SVGPathSeg"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Paths.SVGPathSeg κλάση. Το interface SVGPathSeg είναι μια βασική διεπαφή που αντιστοιχεί σε μια ενιαία εντολή μέσα σε μια προδιαγραφή δεδομένων διαδρομής"
type: docs
weight: 4560
url: /el/net/aspose.svg.paths/svgpathseg/
---
## SVGPathSeg class

Η διεπαφή SVGPathSeg είναι μια βασική διεπαφή που αντιστοιχεί σε μια εντολή εντός του προτύπου δεδομένων μονοπατιού.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [PathSegType](../../aspose.svg.paths/svgpathseg/pathsegtype/) { get; } | Ο τύπος του τμήματος διαδρομής όπως καθορίζεται από μία από τις σταθερές που ορίζονται σε αυτή τη διεπαφή. |
| [PathSegTypeAsLetter](../../aspose.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | Ο τύπος του τμήματος διαδρομής, καθορισμένος από το αντίστοιχο όνομα εντολής ενός χαρακτήρα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_arc_abs/) | Αντιστοιχεί σε μια "απόλυτη arcto" (A) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_ARC_REL](../../aspose.svg.paths/svgpathseg/pathseg_arc_rel/) | Αντιστοιχεί σε μια "σχετική arcto" (a) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CLOSEPATH](../../aspose.svg.paths/svgpathseg/pathseg_closepath/) | Αντιστοιχεί σε μια "closepath" (z) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Αντιστοιχεί σε μια "απόλυτη cubic Bézier curveto" (C) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Αντιστοιχεί σε μια "σχετική cubic Bézier curveto" (c) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Αντιστοιχεί σε μια "απόλυτη smooth cubic curveto" (S) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Αντιστοιχεί σε μια "σχετική smooth cubic curveto" (s) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Αντιστοιχεί σε μια "απόλυτη quadratic Bézier curveto" (Q) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Αντιστοιχεί σε μια "σχετική quadratic Bézier curveto" (q) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Αντιστοιχεί σε μια "απόλυτη smooth quadratic curveto" (T) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Αντιστοιχεί σε μια "σχετική smooth quadratic curveto" (t) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_LINETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_abs/) | Αντιστοιχεί σε μια "απόλυτη lineto" (L) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Αντιστοιχεί σε μια "απόλυτη horizontal lineto" (H) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Αντιστοιχεί σε μια "σχετική horizontal lineto" (h) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_LINETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_rel/) | Αντιστοιχεί σε μια "σχετική lineto" (l) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Αντιστοιχεί σε μια "απόλυτη vertical lineto" (V) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Αντιστοιχεί σε μια "σχετική vertical lineto" (v) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_MOVETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_moveto_abs/) | Αντιστοιχεί σε μια "απόλυτη moveto" (M) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_MOVETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_moveto_rel/) | Αντιστοιχεί σε μια "σχετική moveto" (m) εντολή δεδομένων διαδρομής. |
| const [PATHSEG_UNKNOWN](../../aspose.svg.paths/svgpathseg/pathseg_unknown/) | Ο τύπος μονάδας δεν είναι ένας από τους προκαθορισμένους τύπους. Είναι άκυρο να προσπαθήσετε να ορίσετε μια νέα τιμή αυτού του τύπου ή να προσπαθήσετε να αλλάξετε μια υπάρχουσα τιμή σε αυτόν τον τύπο. |

### Δείτε επίσης

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
