---
title: "EventTarget.AddEventListener"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος EventTarget AddEventListener. Ορίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο"
type: docs
weight: 20
url: /el/net/aspose.svg.dom/eventtarget/addeventlistener/
---
## AddEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#addeventlistener}

Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο.

Λειτουργεί προσθέτοντας μια συνάρτηση ή ένα αντικείμενο που υλοποιεί [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), στη λίστα των ακροατών συμβάντων για τον καθορισμένο τύπο συμβάντος στο [`EventTarget`](../) στο οποίο καλείται. Εάν η συνάρτηση ή το αντικείμενο βρίσκεται ήδη στη λίστα των ακροατών για αυτόν τον στόχο, δεν προστίθενται δεύτερη φορά.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος συμβάντος για τον οποίο ο χρήστης καταχωρεί. |
| handler | DOMEventHandler | Δέχεται ένα [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) που θα κληθεί όταν συμβεί το γεγονός. |
| useCapture | Boolean | Εάν είναι true, το useCapture υποδεικνύει ότι ο χρήστης επιθυμεί να ξεκινήσει τη σύλληψη. Μετά την έναρξη της σύλληψης, όλα τα συμβάντα του καθορισμένου τύπου θα διανεμηθούν στον καταχωρημένο [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) πριν διανεμηθούν σε οποιοδήποτε Event Target κάτω από αυτά στο δέντρο. Τα συμβάντα που ανεβαίνουν μέσω του δέντρου δεν θα ενεργοποιήσουν έναν [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που έχει οριστεί να χρησιμοποιεί σύλληψη. |

## Παρατηρήσεις

Εάν ένας [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) προστεθεί σε ένα [`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες αλλά μπορεί να ενεργοποιηθεί σε μεταγενέστερο στάδιο της ροής του συμβάντος, όπως η φάση bubbling.

Εάν πολλαπλοί πανομοιότυποι Event Listeners καταχωρηθούν στο ίδιο [`EventTarget`](../) με τις ίδιες παραμέτρους, οι διπλότυπες εμφανίσεις απορρίπτονται. Δεν προκαλούν την κλήση του [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) δύο φορές και επειδή απορρίπτονται, δεν χρειάζεται να αφαιρεθούν με τη μέθοδο [`RemoveEventListener`](../removeeventlistener/).

### Δείτε επίσης

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#addeventlistener_1}

Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο.

Λειτουργεί προσθέτοντας μια συνάρτηση ή ένα αντικείμενο που υλοποιεί [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), στη λίστα των ακροατών συμβάντων για τον καθορισμένο τύπο συμβάντος στο [`EventTarget`](../) στο οποίο καλείται. Εάν η συνάρτηση ή το αντικείμενο βρίσκεται ήδη στη λίστα των ακροατών για αυτόν τον στόχο, δεν προστίθενται δεύτερη φορά.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος συμβάντος για τον οποίο ο χρήστης καταχωρεί. |
| listener | IEventListener | Δέχεται μια διεπαφή που υλοποιείται από τον χρήστη και περιέχει τις μεθόδους που θα κληθούν όταν συμβεί το συμβάν. |

## Παρατηρήσεις

Εάν ένας [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) προστεθεί σε ένα [`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες αλλά μπορεί να ενεργοποιηθεί σε μεταγενέστερο στάδιο της ροής του συμβάντος, όπως η φάση bubbling.

Εάν πολλαπλοί πανομοιότυποι Event Listeners καταχωρηθούν στο ίδιο [`EventTarget`](../) με τις ίδιες παραμέτρους, οι διπλότυπες εμφανίσεις απορρίπτονται. Δεν προκαλούν την κλήση του [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) δύο φορές και επειδή απορρίπτονται, δεν χρειάζεται να αφαιρεθούν με τη μέθοδο [`RemoveEventListener`](../removeeventlistener/).

### Δείτε επίσης

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#addeventlistener_2}

Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο.

Λειτουργεί προσθέτοντας μια συνάρτηση ή ένα αντικείμενο που υλοποιεί [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), στη λίστα των ακροατών συμβάντων για τον καθορισμένο τύπο συμβάντος στο [`EventTarget`](../) στο οποίο καλείται. Εάν η συνάρτηση ή το αντικείμενο βρίσκεται ήδη στη λίστα των ακροατών για αυτόν τον στόχο, δεν προστίθενται δεύτερη φορά.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος συμβάντος για τον οποίο ο χρήστης καταχωρεί. |
| listener | IEventListener | Δέχεται μια διεπαφή που υλοποιείται από τον χρήστη και περιέχει τις μεθόδους που θα κληθούν όταν συμβεί το συμβάν. |
| useCapture | Boolean | Εάν είναι true, το useCapture υποδεικνύει ότι ο χρήστης επιθυμεί να ξεκινήσει τη σύλληψη. Μετά την έναρξη της σύλληψης, όλα τα συμβάντα του καθορισμένου τύπου θα διανεμηθούν στον καταχωρημένο [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) πριν διανεμηθούν σε οποιοδήποτε Event Target κάτω από αυτά στο δέντρο. Τα συμβάντα που ανεβαίνουν μέσω του δέντρου δεν θα ενεργοποιήσουν έναν [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που έχει οριστεί να χρησιμοποιεί σύλληψη. |

## Παρατηρήσεις

Εάν ένας [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) προστεθεί σε ένα [`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες αλλά μπορεί να ενεργοποιηθεί σε μεταγενέστερο στάδιο της ροής του συμβάντος, όπως η φάση bubbling.

Εάν πολλαπλοί πανομοιότυποι Event Listeners καταχωρηθούν στο ίδιο [`EventTarget`](../) με τις ίδιες παραμέτρους, οι διπλότυπες εμφανίσεις απορρίπτονται. Δεν προκαλούν την κλήση του [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) δύο φορές και επειδή απορρίπτονται, δεν χρειάζεται να αφαιρεθούν με τη μέθοδο [`RemoveEventListener`](../removeeventlistener/).

### Δείτε επίσης

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
