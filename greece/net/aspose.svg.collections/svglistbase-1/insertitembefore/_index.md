---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος InsertItemBefore του SVGListBase. Εισάγει ένα νέο στοιχείο στη λίστα στη συγκεκριμένη θέση. Το πρώτο στοιχείο είναι ο αριθμός 0"
type: docs
weight: 90
url: /el/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase<T>.InsertItemBefore method

Εισάγει ένα νέο στοιχείο στη λίστα στη καθορισμένη θέση. Το πρώτο στοιχείο είναι ο αριθμός 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newItem | T | Το στοιχείο που πρόκειται να εισαχθεί στη λίστα. |
| δείκτης | UInt64 | Ο δείκτης του στοιχείου πριν από το οποίο θα εισαχθεί το νέο στοιχείο. Το πρώτο στοιχείο είναι ο αριθμός 0. Εάν ο δείκτης είναι ίσος με 0, τότε το νέο στοιχείο εισάγεται στην αρχή της λίστας. Εάν ο δείκτης είναι μεγαλύτερος ή ίσος με το numberOfItems, τότε το νέο στοιχείο προστίθεται στο τέλος της λίστας. |

### Τιμή Επιστροφής

Το εισαχθέν στοιχείο.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
