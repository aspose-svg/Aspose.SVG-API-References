---
title: "Διεπαφή IMatrix"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Διεπαφή Aspose.Svg.Drawing.IMatrix. Αντιπροσωπεύει έναν πίνακα που χρησιμοποιείται για μετασχηματισμούς."
type: docs
weight: 3500
url: /el/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Αντιπροσωπεύει έναν πίνακα που χρησιμοποιείται για μετασχηματισμούς.

```csharp
public interface IMatrix
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο πίνακας είναι ο μοναδιαίος πίνακας. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο πίνακας είναι αντιστρέψιμος. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Λαμβάνει ή ορίζει την τιμή στην πρώτη γραμμή και πρώτη στήλη του πίνακα. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Λαμβάνει ή ορίζει την τιμή στην πρώτη γραμμή και δεύτερη στήλη του πίνακα. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Λαμβάνει ή ορίζει την τιμή στη δεύτερη γραμμή και πρώτη στήλη του πίνακα. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Λαμβάνει ή ορίζει την τιμή στη δεύτερη γραμμή και δεύτερη στήλη του πίνακα. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Λαμβάνει ή ορίζει την τιμή στην τρίτη γραμμή και πρώτη στήλη του πίνακα. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Λαμβάνει ή ορίζει την τιμή στην τρίτη γραμμή και δεύτερη στήλη του πίνακα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Δημιουργεί ένα αντίγραφο αυτού του πίνακα. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Λαμβάνει τα στοιχεία του πίνακα ως έναν πίνακα. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Αντιστρέφει αυτόν τον πίνακα. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Πολλαπλασιάζει αυτόν τον πίνακα με έναν άλλο πίνακα. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Πολλαπλασιάζει αυτόν τον πίνακα με έναν άλλο πίνακα με την καθορισμένη σειρά. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Επαναφέρει τον πίνακα στον μοναδιαίο πίνακα. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Περιστρέφει τον πίνακα κατά τη καθορισμένη γωνία. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Περιστρέφει τον πίνακα κατά τη καθορισμένη γωνία με τη καθορισμένη σειρά. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Περιστρέφει τον πίνακα κατά τη καθορισμένη γωνία γύρω από το καθορισμένο σημείο. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Περιστρέφει τον πίνακα κατά τη καθορισμένη γωνία γύρω από το καθορισμένο σημείο με τη καθορισμένη σειρά. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Κλιμακώνει τον πίνακα με τους καθορισμένους συντελεστές κλίμακας ομοιόμορφα. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Κλιμακώνει τον πίνακα με τους καθορισμένους συντελεστές κλίμακας με τη καθορισμένη σειρά. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Εφαρμόζει μια παραμόρφωση κλίσης στον πίνακα. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Μετασχηματίζει το καθορισμένο σημείο χρησιμοποιώντας αυτόν τον πίνακα. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Μετασχηματίζει έναν πίνακα σημείων χρησιμοποιώντας αυτόν τον πίνακα. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Μετασχηματίζει το καθορισμένο ορθογώνιο χρησιμοποιώντας αυτόν τον πίνακα. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Μετατοπίζει τον πίνακα κατά τις καθορισμένες τιμές μετατόπισης. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Μεταφράζει τον πίνακα κατά τις καθορισμένες τιμές μετατόπισης με την καθορισμένη σειρά. |

### Δείτε επίσης

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
