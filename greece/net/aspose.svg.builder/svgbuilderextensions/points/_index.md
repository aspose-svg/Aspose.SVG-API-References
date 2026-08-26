---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions Points. Ορίζει το χαρακτηριστικό points για ένα στοιχείο SVG χρησιμοποιώντας έναν πίνακα διπλών (double)."
type: docs
weight: 1910
url: /el/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

Ορίζει το χαρακτηριστικό 'points' για ένα στοιχείο SVG χρησιμοποιώντας έναν πίνακα διπλών τιμών.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| σημεία | Ένας πίνακας διπλών που αντιπροσωπεύει τα σημεία (πρέπει να είναι άρτιος αριθμός). |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εκτοπίζεται εάν δοθεί περιττός αριθμός σημείων. |

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

Ορίζει το χαρακτηριστικό 'points' για ένα στοιχείο SVG χρησιμοποιώντας έναν πίνακα αντικειμένων PointF.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| σημεία | Ένας πίνακας αντικειμένων PointF που αντιπροσωπεύουν τα σημεία. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
