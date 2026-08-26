---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "IDocumentTraversal CreateNodeIterator method. Δημιουργεί έναν νέο NodeIterator πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο"
type: docs
weight: 10
url: /el/net/aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/)*) {#createnodeiterator}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | node που θα επαναληφθεί μαζί με τα παιδιά του. Ο iterator αρχικά τοποθετείται ακριβώς πριν από αυτό το node. Οι σημαίες whatToShow και το filter, εάν υπάρχουν, δεν λαμβάνονται υπόψη κατά τον καθορισμό αυτής της θέσης. Το root δεν πρέπει να είναι null. |

### Τιμή Επιστροφής

Ο νεοδημιουργημένος NodeIterator.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν το καθορισμένο root είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long*) {#createnodeiterator_1}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | node που θα επαναληφθεί μαζί με τα παιδιά του. Ο iterator αρχικά τοποθετείται ακριβώς πριν από αυτό το node. Οι σημαίες whatToShow και το filter, εάν υπάρχουν, δεν λαμβάνονται υπόψη κατά τον καθορισμό αυτής της θέσης. Το root δεν πρέπει να είναι null. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορεί να εμφανίζονται στην λογική προβολή του δέντρου που παρουσιάζεται από τον επαναλήπτη. Δείτε την περιγραφή του NodeFilter για το σύνολο των πιθανών τιμών SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |

### Τιμή Επιστροφής

Ο νεοδημιουργημένος NodeIterator.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν το καθορισμένο root είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createnodeiterator_2}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | node που θα επαναληφθεί μαζί με τα παιδιά του. Ο iterator αρχικά τοποθετείται ακριβώς πριν από αυτό το node. Οι σημαίες whatToShow και το filter, εάν υπάρχουν, δεν λαμβάνονται υπόψη κατά τον καθορισμό αυτής της θέσης. Το root δεν πρέπει να είναι null. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορεί να εμφανίζονται στην λογική προβολή του δέντρου που παρουσιάζεται από τον επαναλήπτη. Δείτε την περιγραφή του NodeFilter για το σύνολο των πιθανών τιμών SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |
| filter | INodeFilter | NodeFilter που θα χρησιμοποιηθεί με αυτό το TreeWalker, ή null για να υποδεικνύει ότι δεν υπάρχει φίλτρο. |

### Τιμή Επιστροφής

Ο νεοδημιουργημένος NodeIterator.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν το καθορισμένο root είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
