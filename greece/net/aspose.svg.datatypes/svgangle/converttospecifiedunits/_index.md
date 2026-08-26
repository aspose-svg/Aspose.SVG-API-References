---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGAngle ConvertToSpecifiedUnits. Διατηρεί την ίδια υποκείμενη αποθηκευμένη τιμή αλλά επαναφέρει το αποθηκευμένο αναγνωριστικό μονάδας στον δοσμένο unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString μπορεί να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου."
type: docs
weight: 50
url: /el/net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρετε το αποθηκευμένο αναγνωριστικό μονάδας στο δοσμένο unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString μπορεί να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | Ο τύπος μονάδας στον οποίο θα μεταβείτε (π.χ., SVG_ANGLETYPE_DEG). |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Εμφανίζεται εάν το unitType είναι SVG_ANGLETYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_ANGLETYPE_* που ορίζονται σε αυτή τη διεπαφή). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Εμφανίζεται όταν η γωνία αντιστοιχεί σε χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
