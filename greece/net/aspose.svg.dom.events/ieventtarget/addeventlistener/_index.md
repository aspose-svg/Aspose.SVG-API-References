---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος IEventTarget AddEventListener. Αυτή η μέθοδος επιτρέπει την καταχώρηση ακροατών συμβάντων στο αντικείμενο-στόχο."
type: docs
weight: 10
url: /el/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

Αυτή η μέθοδος επιτρέπει την εγγραφή ακροατών συμβάντων στον στόχο συμβάντος.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος συμβάντος για τον οποίο ο χρήστης καταχωρεί. |
| listener | IEventListener | Δέχεται μια διεπαφή που υλοποιείται από τον χρήστη και περιέχει τις μεθόδους που θα κληθούν όταν συμβεί το συμβάν. |

## Παρατηρήσεις

Εάν ένα [`IEventListener`](../../ieventlistener/) προστεθεί σε ένα [`EventTarget`](../../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες αλλά μπορεί να ενεργοποιηθεί σε μεταγενέστερο στάδιο της ροής του συμβάντος, όπως η φάση ανόδου.

Εάν πολλαπλοί ταυτόσημοι Event Listeners καταχωρηθούν στο ίδιο [`EventTarget`](../../../aspose.svg.dom/eventtarget/) με τις ίδιες παραμέτρους, οι διπλότυπες παρουσίες απορρίπτονται. Δεν προκαλούν το [`IEventListener`](../../ieventlistener/) να κληθεί δύο φορές και, επειδή απορρίπτονται, δεν χρειάζεται να αφαιρεθούν με τη μέθοδο [`RemoveEventListener`](../removeeventlistener/).

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

Αυτή η μέθοδος επιτρέπει την εγγραφή ακροατών συμβάντων στον στόχο συμβάντος.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος συμβάντος για τον οποίο ο χρήστης καταχωρεί. |
| listener | IEventListener | Δέχεται μια διεπαφή που υλοποιείται από τον χρήστη και περιέχει τις μεθόδους που θα κληθούν όταν συμβεί το συμβάν. |
| useCapture | Boolean | Εάν είναι true, το useCapture υποδεικνύει ότι ο χρήστης επιθυμεί να ξεκινήσει τη σύλληψη. Μετά την έναρξη της σύλληψης, όλα τα συμβάντα του καθορισμένου τύπου θα αποστέλλονται στον καταχωρημένο [`IEventListener`](../../ieventlistener/) πριν αποσταλούν σε οποιουσδήποτε Event Targets που βρίσκονται κάτω από αυτούς στο δέντρο. Τα συμβάντα που ανεβαίνουν μέσω του δέντρου δεν θα ενεργοποιούν έναν [`IEventListener`](../../ieventlistener/) που έχει οριστεί να χρησιμοποιεί σύλληψη. |

## Παρατηρήσεις

Εάν ένα [`IEventListener`](../../ieventlistener/) προστεθεί σε ένα [`EventTarget`](../../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες αλλά μπορεί να ενεργοποιηθεί σε μεταγενέστερο στάδιο της ροής του συμβάντος, όπως η φάση ανόδου.

Εάν πολλαπλοί ταυτόσημοι Event Listeners καταχωρηθούν στο ίδιο [`EventTarget`](../../../aspose.svg.dom/eventtarget/) με τις ίδιες παραμέτρους, οι διπλότυπες παρουσίες απορρίπτονται. Δεν προκαλούν το [`IEventListener`](../../ieventlistener/) να κληθεί δύο φορές και, επειδή απορρίπτονται, δεν χρειάζεται να αφαιρεθούν με τη μέθοδο [`RemoveEventListener`](../removeeventlistener/).

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
