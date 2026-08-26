---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Combine του SVGGeometryElement. Συνδυάζει αυτή τη γεωμετρία με άλλη γεωμετρία SVG χρησιμοποιώντας λογική λειτουργία και επιστρέφει ένα νέο στοιχείο διαδρομής που περιέχει το αποτέλεσμα."
type: docs
weight: 20
url: /el/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Συνδυάζει αυτή τη γεωμετρία με άλλη γεωμετρία SVG χρησιμοποιώντας λογική πράξη και επιστρέφει ένα νέο στοιχείο `<path>` που περιέχει το αποτέλεσμα.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | Η άλλη γεωμετρία με την οποία θα συνδυαστεί. Πρέπει να βρίσκεται στο ίδιο έγγραφο. |
| op | BooleanPathOp | Ο λογικός τελεστής που θα εφαρμοστεί: Union (A UNION B), Difference (A - B), Intersection (A INTERSECT B), ή Exclusion (XOR). |

### Τιμή Επιστροφής

Ένα νέο [`SVGPathElement`](../../svgpathelement/) του οποίου το χαρακτηριστικό `d` κωδικοποιεί το αποτέλεσμα στον ριζικό χώρο χρήστη `<svg>` (CSS px). Το στοιχείο δεν προσαρμόζεται στο DOM.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentNullException | Εκτοξεύεται εάν το *geometryElement* είναι null. |
| InvalidOperationException | Εκτοπίζεται εάν αυτό το στοιχείο δεν έχει έγγραφο ιδιοκτήτη. |
| NotSupportedException | Εκτοπίζεται όταν οι λογικές λειτουργίες διαδρομής δεν είναι διαθέσιμες· αυτή η δυνατότητα απαιτεί το backend SkiaSharp (εγκαταστήστε το πακέτο Aspose.SVG.Drawing.SkiaSharp). |

### Δείτε επίσης

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
