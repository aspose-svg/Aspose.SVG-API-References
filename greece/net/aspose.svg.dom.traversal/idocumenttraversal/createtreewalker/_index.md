---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "IDocumentTraversal CreateTreeWalker method. Δημιουργεί έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο"
type: docs
weight: 20
url: /el/net/aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/)*) {#createtreewalker}

Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | Κόμβος που θα λειτουργήσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής· οποιοσδήποτε τύπος κόμβου θα γίνει αποδεκτός ως ρίζα. Το currentNode του TreeWalker αρχικοποιείται σε αυτόν τον κόμβο, ανεξάρτητα από το αν είναι ορατό. Η ρίζα λειτουργεί ως σημείο τερματισμού για μεθόδους διάσχισης που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα δεν πρέπει να είναι null. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο TreeWalker.

### Δείτε επίσης

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long*) {#createtreewalker_1}

Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | Κόμβος που θα λειτουργήσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής· οποιοσδήποτε τύπος κόμβου θα γίνει αποδεκτός ως ρίζα. Το currentNode του TreeWalker αρχικοποιείται σε αυτόν τον κόμβο, ανεξάρτητα από το αν είναι ορατό. Η ρίζα λειτουργεί ως σημείο τερματισμού για μεθόδους διάσχισης που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορεί να εμφανιστούν στην λογική προβολή του δέντρου που παρουσιάζεται από το tree-walker. Δείτε την περιγραφή του NodeFilter για το σύνολο των πιθανών τιμών SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο TreeWalker.

### Δείτε επίσης

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createtreewalker_2}

Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | Κόμβος που θα λειτουργήσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής· οποιοσδήποτε τύπος κόμβου θα γίνει αποδεκτός ως ρίζα. Το currentNode του TreeWalker αρχικοποιείται σε αυτόν τον κόμβο, ανεξάρτητα από το αν είναι ορατό. Η ρίζα λειτουργεί ως σημείο τερματισμού για μεθόδους διάσχισης που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορεί να εμφανιστούν στην λογική προβολή του δέντρου που παρουσιάζεται από το tree-walker. Δείτε την περιγραφή του NodeFilter για το σύνολο των πιθανών τιμών SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |
| filter | INodeFilter | NodeFilter που θα χρησιμοποιηθεί με αυτό το TreeWalker, ή null για να υποδεικνύει ότι δεν υπάρχει φίλτρο. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο TreeWalker.

### Δείτε επίσης

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
