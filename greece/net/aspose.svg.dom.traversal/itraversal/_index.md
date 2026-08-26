---
title: "Διεπαφή ITraversal"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Traversal.ITraversal interface. Οι επαναλήπτες χρησιμοποιούνται για να προχωρούν μέσα σε ένα σύνολο κόμβων, π.χ. το σύνολο των κόμβων σε ένα NodeList, το υποδέντρο του εγγράφου που διέπεται από έναν συγκεκριμένο Node, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που θα επαναληφθούν καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 ορίζει μια μοναδική υλοποίηση του NodeIterator για διασχίσεις με σειρά εγγράφου ενός υποδέντρου εγγράφου. Παραδείγματα αυτών των επαναλήπτων δημιουργούνται με κλήση του DocumentTraversal .createNodeIterator."
type: docs
weight: 3260
url: /el/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

Οι επαναλήπτες χρησιμοποιούνται για να προχωρούν μέσα σε ένα σύνολο κόμβων, π.χ. το σύνολο κόμβων σε μια NodeList, το υποδέντρο του εγγράφου που διέπεται από έναν συγκεκριμένο Node, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που θα επαναληφθεί καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 ορίζει μια μοναδική υλοποίηση NodeIterator για τη διέλευση κατά σειρά εγγράφου ενός υποδέντρου εγγράφου. Παραδείγματα αυτών των επαναληπτών δημιουργούνται καλώντας το DocumentTraversal .createNodeIterator().

Δείτε επίσης το [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | Το NodeFilter που χρησιμοποιείται για το φιλτράρισμα των κόμβων. |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | Ο ριζικός κόμβος του NodeIterator, όπως ορίστηκε όταν δημιουργήθηκε. |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | Αυτό το χαρακτηριστικό καθορίζει ποιους τύπους κόμβων παρουσιάζονται μέσω του επαναλήπτη. Το διαθέσιμο σύνολο σταθερών ορίζεται στη διεπαφή NodeFilter. Οι κόμβοι που δεν γίνονται αποδεκτοί από το whatToShow θα παραλειφθούν, αλλά τα παιδιά τους μπορεί ακόμη να ληφθούν υπόψη. Σημειώστε ότι αυτή η παράλειψη έχει προτεραιότητα έναντι του φίλτρου, εάν υπάρχει. |

### Δείτε επίσης

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
