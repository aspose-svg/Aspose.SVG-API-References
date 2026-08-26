---
title: "Node.RemoveChild"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Node.RemoveChild. Αφαιρεί έναν παιδικό κόμβο από το DOM και επιστρέφει τον αφαιρεθέντα κόμβο."
type: docs
weight: 270
url: /el/net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

Αφαιρεί έναν κόμβο-παιδί από το DOM και επιστρέφει τον αφαιρεθέντα κόμβο.

Σημείωση: Εφόσον διατηρείται μια αναφορά στο αφαιρεθέν παιδί, παραμένει στη μνήμη, αλλά δεν αποτελεί πλέον μέρος του DOM. Μπορεί να χρησιμοποιηθεί ξανά αργότερα στον κώδικα. Εάν η τιμή επιστροφής της `RemoveChild` δεν αποθηκευτεί και δεν υπάρχει άλλη αναφορά, θα διαγραφεί αυτόματα από τη μνήμη μετά από λίγο χρόνο.

```csharp
public Node RemoveChild(Node child)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| child | Node | Ένα [`Node`](../) που είναι ο παιδικός κόμβος που θα αφαιρεθεί από το DOM. |

### Τιμή Επιστροφής

Σε αντίθεση με το [`CloneNode`](../clonenode/), η τιμή επιστροφής διατηρεί τα αντικείμενα [`EventListener`](../../../aspose.svg.dom.events/ieventlistener/) που σχετίζονται με αυτό.

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
