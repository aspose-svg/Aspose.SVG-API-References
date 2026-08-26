---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "IXPathResult SnapshotItem method. Επιστρέφει το στοιχείο με το δείκτη στην συλλογή στιγμιότυπου. Εάν το index είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει null. Σε αντίθεση με το αποτέλεσμα του επαναλήπτη, το στιγμιότυπο δεν γίνεται άκυρο αλλά μπορεί να μην αντιστοιχεί στο τρέχον έγγραφο εάν αυτό τροποποιηθεί."
type: docs
weight: 90
url: /el/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Επιστρέφει το στοιχείο `index` στη συλλογή στιγμιότυπου. Εάν το `index` είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει `null`. Σε αντίθεση με το αποτέλεσμα του επαναλήπτη, το στιγμιότυπο δεν γίνεται άκυρο, αλλά μπορεί να μην αντιστοιχεί στο τρέχον έγγραφο εάν αυτό τροποποιηθεί.

```csharp
public Node SnapshotItem(int index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | Int32 | Δείκτης στη συλλογή στιγμιότυπου. |

### Τιμή Επιστροφής

Ο κόμβος στη θέση `index` στο `NodeList`, ή `null` εάν αυτό δεν είναι έγκυρος δείκτης.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: προκαλείται εάν `resultType` δεν είναι τύπου `UnorderedNodeSnapshot` ή `OrderedNodeSnapshot`. |

### Δείτε επίσης

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
