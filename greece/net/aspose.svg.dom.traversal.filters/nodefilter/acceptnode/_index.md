---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "NodeFilter AcceptNode method. Δοκιμάζει αν ένας συγκεκριμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· δεν καλείται συνήθως απευθείας από κώδικα χρήστη. Ωστόσο, μπορείτε να το κάνετε αν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της δικής σας εφαρμογής"
type: docs
weight: 10
url: /el/net/aspose.svg.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Δοκιμάστε αν ένας καθορισμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· δεν καλείται συνήθως απευθείας από κώδικα χρήστη. (Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της δικής σας εφαρμογής.)

```csharp
public abstract short AcceptNode(Node n)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| n | Node | κόμβος για να ελεγχθεί αν περνάει το φίλτρο ή όχι. |

### Τιμή Επιστροφής

μια σταθερά για τον καθορισμό του αν ο κόμβος είναι αποδεκτός, απορριφθεί ή παραληφθεί, όπως ορίζεται παραπάνω.

### Δείτε επίσης

* class [Node](../../../aspose.svg.dom/node/)
* class [NodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../../)
