---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος AcceptNode του INodeFilter. Ελέγχει εάν ένας συγκεκριμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· δεν καλείται συνήθως απευθείας από τον κώδικα του χρήστη. Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της δικής σας εφαρμογής."
type: docs
weight: 10
url: /el/net/aspose.svg.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Δοκιμάστε αν ένας καθορισμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· δεν καλείται συνήθως απευθείας από κώδικα χρήστη. (Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της δικής σας εφαρμογής.)

```csharp
public short AcceptNode(Node n)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| n | Node | κόμβος για να ελεγχθεί αν περνάει το φίλτρο ή όχι. |

### Τιμή Επιστροφής

μια σταθερά για τον καθορισμό του αν ο κόμβος είναι αποδεκτός, απορριφθεί ή παραληφθεί, όπως ορίζεται παραπάνω.

### Δείτε επίσης

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
