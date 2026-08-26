---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGFEColorMatrixElementBuilder TypeAndValues μέθοδος. Ορίζει τα χαρακτηριστικά type και values του στοιχείου feColorMatrix, καθορίζοντας τη λειτουργία του χρωματικού πίνακα και τις παραμέτρους του"
type: docs
weight: 30
url: /el/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Ορίζει τις ιδιότητες 'type' και 'values' του στοιχείου feColorMatrix, καθορίζοντας τη λειτουργία του χρωματικού πίνακα και τις παραμέτρους του.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | ColorMatrixOperation | Η τιμή enum ColorMatrixOperation που αντιπροσωπεύει τον τύπο της λειτουργίας χρωματικού πίνακα. |
| τιμές | Double[] | Οι παράμετροι για τη λειτουργία του χρωματικού πίνακα. |

### Τιμή Επιστροφής

Η τρέχουσα παρουσία του builder.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν οι παρεχόμενες τιμές δεν ταιριάζουν με τις απαιτήσεις του καθορισμένου τύπου. |
| NotSupportedException | Εκτοπίζεται όταν παρέχεται ένας μη υποστηριζόμενος τύπος λειτουργίας πίνακα. |

### Δείτε επίσης

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
