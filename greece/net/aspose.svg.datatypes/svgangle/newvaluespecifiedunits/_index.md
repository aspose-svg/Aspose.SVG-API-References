---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος NewValueSpecifiedUnits του SVGAngle. Επαναφέρει την τιμή ως αριθμό με σχετική unitType, αντικαθιστώντας έτσι τις τιμές όλων των χαρακτηριστικών του αντικειμένου."
type: docs
weight: 60
url: /el/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Επαναφέρετε την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newUnitType | UInt16 | Ο τύπος μονάδας για την τιμή (π.χ., SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Η τιμή της γωνίας. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Εμφανίζεται εάν το unitType είναι SVG_ANGLETYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_ANGLETYPE_* που ορίζονται σε αυτή τη διεπαφή). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Εμφανίζεται όταν η γωνία αντιστοιχεί σε χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
