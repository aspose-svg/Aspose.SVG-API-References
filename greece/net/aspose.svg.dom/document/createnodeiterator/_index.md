---
title: "Document.CreateNodeIterator"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Document μέθοδος CreateNodeIterator. Δημιουργεί έναν νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο node"
type: docs
weight: 900
url: /el/net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../node/)*) {#createnodeiterator}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν το καθορισμένο root είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long*) {#createnodeiterator_1}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν το καθορισμένο root είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createnodeiterator_2}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν το καθορισμένο root είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
