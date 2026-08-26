---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος IEventTarget DispatchEvent. Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων της υλοποίησης."
type: docs
weight: 20
url: /el/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων της υλοποίησης.

```csharp
public bool DispatchEvent(Event @event)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | Γεγονός | Καθορίζει τον τύπο του συμβάντος, τη συμπεριφορά και τις συμφραζόμενες πληροφορίες που θα χρησιμοποιηθούν στην επεξεργασία του συμβάντος. |

### Τιμή Επιστροφής

Η τιμή επιστροφής του [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) υποδεικνύει εάν κάποιοι από τους ακροατές που επεξεργάστηκαν το συμβάν κάλεσαν το [`PreventDefault`](../../event/preventdefault/). Εάν κλήθηκε το [`PreventDefault`](../../event/preventdefault/), η τιμή είναι false, αλλιώς η τιμή είναι true.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

## Παρατηρήσεις

Τα συμβάντα που αποστέλλονται με αυτόν τον τρόπο θα έχουν την ίδια συμπεριφορά σύλληψης και ανόδου όπως τα συμβάντα που αποστέλλονται άμεσα από την υλοποίηση. Ο στόχος του συμβάντος είναι το [`EventTarget`](../../../aspose.svg.dom/eventtarget/) στο οποίο κλήθηκε το [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/).

### Δείτε επίσης

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
