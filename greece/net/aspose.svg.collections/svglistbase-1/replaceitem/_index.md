---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος ReplaceItem του SVGListBase-1. Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο"
type: docs
weight: 110
url: /el/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase<T>.ReplaceItem method

Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newItem | T | Το στοιχείο που πρόκειται να εισαχθεί στη λίστα. |
| δείκτης | UInt64 | Ο δείκτης του στοιχείου που πρόκειται να αντικατασταθεί. Το πρώτο στοιχείο είναι ο αριθμός 0. |

### Τιμή Επιστροφής

Το εισαχθέν στοιχείο.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Εμφανίζεται εάν ο αριθμός δείκτη είναι μεγαλύτερος ή ίσος με το numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
