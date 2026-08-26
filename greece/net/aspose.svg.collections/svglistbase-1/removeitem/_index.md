---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος RemoveItem του SVGListBase. Αφαιρεί ένα υπάρχον στοιχείο από τη λίστα"
type: docs
weight: 100
url: /el/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

Αφαιρεί ένα υπάρχον στοιχείο από τη λίστα.

```csharp
public T RemoveItem(ulong index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | UInt64 | Ο δείκτης του στοιχείου που πρέπει να αφαιρεθεί. Το πρώτο στοιχείο είναι ο αριθμός 0. |

### Τιμή Επιστροφής

Το αφαιρεθέν στοιχείο.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Εμφανίζεται εάν ο αριθμός δείκτη είναι μεγαλύτερος ή ίσος με το numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
