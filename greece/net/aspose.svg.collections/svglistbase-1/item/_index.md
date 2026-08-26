---
title: "SVGListBase-1.Item"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Ιδιότητα Item του SVGListBase. Επιστρέφει το στοιχείο στη θέση index στη λίστα"
type: docs
weight: 10
url: /el/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase<T> indexer

Επιστρέφει το στοιχείο με δείκτη index στη λίστα.

```csharp
public T this[ulong index] { get; set; }
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| δείκτης | Δείκτης στη λίστα. |

### Τιμή Επιστροφής

Το αποθηκευμένο αντικείμενο στη θέση index στη λίστα.

### Property Value

Ο τύπος του στοιχείου που αποθηκεύεται στη λίστα.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Εμφανίζεται εάν ο αριθμός δείκτη είναι μεγαλύτερος ή ίσος με το numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
