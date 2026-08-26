---
title: "ICSSImportRule Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Css.ICSSImportRule διεπαφή. Η διεπαφή CSSImportRule αντιπροσωπεύει έναν κανόνα εισαγωγής μέσα σε ένα φύλλο στυλ CSS. Ο κανόνας εισαγωγής χρησιμοποιείται για την εισαγωγή κανόνων στυλ από άλλα φύλλα στυλ."
type: docs
weight: 2560
url: /el/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

Η διεπαφή CSSImportRule αντιπροσωπεύει έναν κανόνα @import μέσα σε ένα φύλλο στυλ CSS. Ο κανόνας @import χρησιμοποιείται για την εισαγωγή κανόνων στυλ από άλλα φύλλα στυλ.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | Η θέση του φύλλου στυλ που θα εισαχθεί. Το χαρακτηριστικό δεν θα περιέχει τον προσδιοριστή "url(...)" γύρω από το URI. |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | Μια λίστα τύπων μέσων για τους οποίους μπορεί να χρησιμοποιηθεί αυτό το φύλλο στυλ. |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | Το φύλλο στυλ στο οποίο αναφέρεται αυτός ο κανόνας, εάν έχει φορτωθεί. Η τιμή αυτού του χαρακτηριστικού είναι null εάν το φύλλο στυλ δεν έχει ακόμη φορτωθεί ή εάν δεν θα φορτωθεί (π.χ. εάν το φύλλο στυλ προορίζεται για τύπο μέσου που δεν υποστηρίζεται από τον πελάτη). |

### Δείτε επίσης

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
