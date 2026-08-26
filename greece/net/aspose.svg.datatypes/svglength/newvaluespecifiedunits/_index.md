---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGLength NewValueSpecifiedUnits. Επαναφέρει την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου"
type: docs
weight: 60
url: /el/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Επαναφέρετε την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | The unit type for the value. |
| valueInSpecifiedUnits | Single | The new value.. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Εμφανίζεται εάν το unitType είναι SVG_LENGTHTYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτή τη διεπαφή). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Εμφανίζεται όταν το μήκος αντιστοιχεί σε χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
