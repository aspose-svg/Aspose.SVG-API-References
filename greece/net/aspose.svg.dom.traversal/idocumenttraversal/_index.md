---
title: "IDocumentTraversal Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Διεπαφή Aspose.Svg.Dom.Traversal.IDocumentTraversal. Το DocumentTraversal περιέχει μεθόδους που δημιουργούν επαναλήπτες και tree-walkers για την περιήγηση ενός κόμβου και των παιδιών του με σειρά εγγράφου, βάθος-πρώτα, προ-προκαθορισμένη σειρά, η οποία είναι ισοδύναμη με τη σειρά με την οποία εμφανίζονται οι ετικέτες έναρξης στην κειμενική αναπαράσταση του εγγράφου. Σε DOM που υποστηρίζουν τη δυνατότητα Traversal, το DocumentTraversal θα υλοποιείται από τα ίδια αντικείμενα που υλοποιούν τη διεπαφή Document."
type: docs
weight: 3220
url: /el/net/aspose.svg.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

Το DocumentTraversal περιέχει μεθόδους που δημιουργούν επαναλήπτες και περιηγητές δέντρου για τη διέλευση ενός κόμβου και των παιδιών του με τη σειρά του εγγράφου (βάθος πρώτα, προ-διάταξη, η οποία είναι ισοδύναμη με τη σειρά με την οποία εμφανίζονται οι ετικέτες έναρξης στην κειμενική αναπαράσταση του εγγράφου). Σε DOMs που υποστηρίζουν τη λειτουργία Traversal, το DocumentTraversal θα υλοποιείται από τα ίδια αντικείμενα που υλοποιούν τη διεπαφή Document.

Δείτε επίσης το [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(*[Node](../../aspose.svg.dom/node/)*) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(*[Node](../../aspose.svg.dom/node/), long*) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(*[Node](../../aspose.svg.dom/node/)*) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(*[Node](../../aspose.svg.dom/node/), long*) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |

### Δείτε επίσης

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
