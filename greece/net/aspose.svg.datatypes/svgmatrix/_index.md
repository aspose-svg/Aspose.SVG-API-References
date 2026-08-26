---
title: "Κλάση SVGMatrix"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.DataTypes.SVGMatrix class. Πολλές από τις γραφικές λειτουργίες των SVG χρησιμοποιούν πίνακες 2x3 της μορφής a c e b d f, οι οποίοι όταν επεκτείνονται σε πίνακα 3x3 για σκοπούς αριθμητικών πράξεων γίνονται a c e b d f 0 0 1."
type: docs
weight: 2230
url: /el/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Πολλές από τις γραφικές λειτουργίες του SVG χρησιμοποιούν πίνακες 2x3 της μορφής: [a c e] [b d f] οι οποίοι, όταν επεκταθούν σε πίνακα 3x3 για σκοπούς αριθμητικών πράξεων με πίνακες, γίνονται: [a c e] [b d f] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | Το στοιχείο A του πίνακα. |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | Το στοιχείο B του πίνακα. |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | Το στοιχείο C του πίνακα. |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | Το στοιχείο D του πίνακα. |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | Το στοιχείο E του πίνακα. |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | Το στοιχείο F του πίνακα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(*SVGMatrix*) | Εκτελεί πολλαπλασιασμό πινάκων. Αυτός ο πίνακας πολλαπλασιάζεται μετά από έναν άλλο πίνακα, επιστρέφοντας το νέο προκύπτοντα πίνακα. |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(*float*) | Πολλαπλασιάζει μετά μια περιστροφική μετασχηματισμό στον τρέχοντα πίνακα και επιστρέφει τον προκύπτοντα πίνακα. |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(*float*) | Πολλαπλασιάζει μετά μια ομοιόμορφη κλίμακα μετασχηματισμού στον τρέχοντα πίνακα και επιστρέφει τον προκύπτοντα πίνακα. |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(*float, float*) | Εκτελεί post-multiply ενός μη ομοιόμορφου μετασχηματισμού κλίμακας στον τρέχον πίνακα και επιστρέφει τον προκύπτον πίνακα. |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(*float*) | Εκτελεί post-multiply ενός μετασχηματισμού skewX στον τρέχον πίνακα και επιστρέφει τον προκύπτον πίνακα. |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(*float*) | Εκτελεί post-multiply ενός μετασχηματισμού skewY στον τρέχον πίνακα και επιστρέφει τον προκύπτον πίνακα. |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(*float, float*) | Εκτελεί post-multiply ενός μετασχηματισμού μετάφρασης στον τρέχον πίνακα και επιστρέφει τον προκύπτον πίνακα. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
