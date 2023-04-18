---
title: Document.CreateNodeIterator
second_title: Aspose.SVG για Αναφορά API .NET
description: Document μέθοδος. Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .
type: docs
weight: 900
url: /el/net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα επαναληφθεί μαζί με τα παιδιά του. Ο επαναλήπτης είναι αρχικά τοποθετημένος ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |

### Επιστρεφόμενη Αξία

Ο νεοδημιουργημένος NodeIterator.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Svg.Dom](../../document/)
* συνέλευση [Aspose.SVG](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα επαναληφθεί μαζί με τα παιδιά του. Ο επαναλήπτης είναι αρχικά τοποθετημένος ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Το flag καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανίζονται στο τη λογική προβολή του δέντρου που παρουσιάζεται από τον επαναλήπτη. Δείτε την περιγραφή του NodeFilter για το σύνολο των τιμών possible SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |

### Επιστρεφόμενη Αξία

Ο νεοδημιουργημένος NodeIterator.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Svg.Dom](../../document/)
* συνέλευση [Aspose.SVG](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα επαναληφθεί μαζί με τα παιδιά του. Ο επαναλήπτης είναι αρχικά τοποθετημένος ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Το flag καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανίζονται στο τη λογική προβολή του δέντρου που παρουσιάζεται από τον επαναλήπτη. Δείτε την περιγραφή του NodeFilter για το σύνολο των τιμών possible SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |
| filter | INodeFilter | NodeFilter που θα χρησιμοποιηθεί με το this TreeWalker ή null για να υποδείξει ότι δεν υπάρχει φίλτρο. |

### Επιστρεφόμενη Αξία

Ο νεοδημιουργημένος NodeIterator.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Svg.Dom](../../document/)
* συνέλευση [Aspose.SVG](../../../)


