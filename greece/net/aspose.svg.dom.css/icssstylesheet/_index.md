---
title: "ICSSStyleSheet Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Css.ICSSStyleSheet διεπαφή. Η διεπαφή CSSStyleSheet είναι μια συγκεκριμένη διεπαφή που χρησιμοποιείται για την αναπαράσταση ενός φύλλου στυλ CSS, δηλαδή ενός φύλλου στυλ του οποίου ο τύπος περιεχομένου είναι text/css."
type: docs
weight: 2660
url: /el/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Η διεπαφή CSSStyleSheet είναι μια συγκεκριμένη διεπαφή που χρησιμοποιείται για την αναπαράσταση ενός φύλλου στυλ CSS, δηλαδή ενός φύλλου στυλ του τύπου περιεχομένου "text/css".

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | Η λίστα όλων των κανόνων CSS που περιέχονται στο φύλλο στυλ. Αυτό περιλαμβάνει τόσο σύνολα κανόνων όσο και at-rules. |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | Εάν αυτό το φύλλο στυλ προέρχεται από έναν κανόνα @import, το χαρακτηριστικό ownerRule θα περιέχει το CSSImportRule. Σε αυτήν την περίπτωση, το χαρακτηριστικό ownerNode στη διεπαφή StyleSheet θα είναι null. Εάν το φύλλο στυλ προέρχεται από ένα στοιχείο ή μια οδηγία επεξεργασίας, το χαρακτηριστικό ownerRule θα είναι null και το χαρακτηριστικό ownerNode θα περιέχει το Node. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(*int*) | Χρησιμοποιείται για τη διαγραφή ενός κανόνα από το φύλλο στυλ. |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(*string, int*) | Χρησιμοποιείται για την εισαγωγή ενός νέου κανόνα στο φύλλο στυλ. Ο νέος κανόνας τώρα γίνεται μέρος της αλυσίδας. |

### Δείτε επίσης

* interface [IStyleSheet](../istylesheet/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
