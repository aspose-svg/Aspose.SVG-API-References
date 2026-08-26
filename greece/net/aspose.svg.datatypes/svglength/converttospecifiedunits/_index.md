---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGLength ConvertToSpecifiedUnits. Διατηρεί την ίδια υποκείμενη αποθηκευμένη τιμή αλλά επαναφέρει το αποθηκευμένο αναγνωριστικό μονάδας στο δοσμένο unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString μπορεί να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα, εάν η αρχική τιμή ήταν 0,5 cm και η μέθοδος κλήθηκε για μετατροπή σε χιλιοστά, τότε το unitType θα αλλάξει σε SVG_LENGTHTYPE_MM, το valueInSpecifiedUnits θα αλλάξει στην αριθμητική τιμή 5 και το valueAsString θα αλλάξει σε 5mm."
type: docs
weight: 50
url: /el/net/aspose.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Διατηρεί την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρει το αποθηκευμένο αναγνωριστικό μονάδας στο δοσμένο unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα, εάν η αρχική τιμή ήταν "0.5cm" και η μέθοδος κληθεί για μετατροπή σε χιλιοστά, τότε το unitType θα αλλάξει σε SVG_LENGTHTYPE_MM, το valueInSpecifiedUnits θα αλλάξει στην αριθμητική τιμή 5 και το valueAsString θα αλλάξει σε "5mm".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | Ο τύπος μονάδας για μεταβολή (π.χ., SVG_LENGTHTYPE_MM). |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Εμφανίζεται εάν το unitType είναι SVG_LENGTHTYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτή τη διεπαφή). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Εμφανίζεται όταν το μήκος αντιστοιχεί σε χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
