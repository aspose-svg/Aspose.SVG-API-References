---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος EventTarget DispatchEvent. Αποστέλλει ένα Event στο καθορισμένο IEventTarget συγχρονισμένα, ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων, συμπεριλαμβανομένων των φάσεων σύλληψης και προαιρετικής ανάδυσης, εφαρμόζονται επίσης σε συμβάντα που αποστέλλονται χειροκίνητα με το DispatchEvent"
type: docs
weight: 30
url: /el/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Αποστέλλει ένα Event στο καθορισμένο [`IEventTarget`](../../../aspose.svg.dom.events/ieventtarget/), (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένων των φάσεων σύλληψης και προαιρετικής ανάδυσης) εφαρμόζονται επίσης σε συμβάντα που αποστέλλονται χειροκίνητα με το [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/).

```csharp
public bool DispatchEvent(Event @event)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | Γεγονός | Καθορίζει τον τύπο του συμβάντος, τη συμπεριφορά και τις συμφραζόμενες πληροφορίες που θα χρησιμοποιηθούν στην επεξεργασία του συμβάντος. |

### Τιμή Επιστροφής

Η τιμή επιστροφής του `DispatchEvent` υποδεικνύει εάν κάποιον από τους ακροατές που επεξεργάστηκαν το συμβάν κάλεσε το [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/). Εάν κλήθηκε το [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/), η τιμή είναι false, διαφορετικά η τιμή είναι true.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../domexception/) |  |

## Παρατηρήσεις

Τα συμβάντα που αποστέλλονται με αυτόν τον τρόπο θα έχουν την ίδια συμπεριφορά σύλληψης και ανάδυσης όπως τα συμβάντα που αποστέλλονται απευθείας από την υλοποίηση. Ο στόχος του συμβάντος είναι το [`EventTarget`](../) στο οποίο κλήθηκε το `DispatchEvent`.

### Δείτε επίσης

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
