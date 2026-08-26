---
title: "Document.CreateElement"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Document CreateElement. Δημιουργεί το στοιχείο HTML που καθορίζεται από το localName ή ένα HTMLUnknownElement εάν το localName δεν αναγνωρίζεται."
type: docs
weight: 850
url: /el/net/aspose.svg.dom/document/createelement/
---
## Document.CreateElement method

Δημιουργεί το στοιχείο HTML που καθορίζεται από το localName, ή ένα HTMLUnknownElement εάν το localName δεν αναγνωρίζεται.

```csharp
public Element CreateElement(string localName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | String | Μια συμβολοσειρά που καθορίζει τον τύπο του στοιχείου που θα δημιουργηθεί. Το nodeName του δημιουργημένου στοιχείου αρχικοποιείται με την τιμή του localName. Μην χρησιμοποιείτε πλήρη ονόματα (π.χ. \"html:a\") με αυτή τη μέθοδο. Όταν κληθεί σε ένα έγγραφο HTML, η createElement() μετατρέπει το localName σε πεζά πριν δημιουργήσει το στοιχείο. |

### Τιμή Επιστροφής

Το νέο [`Element`](../../element/).

### Δείτε επίσης

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
