---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος IEventTarget RemoveEventListener. Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από το αντικείμενο-στόχο. Εάν ένας IEventListener αφαιρεθεί από ένα EventTarget ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους."
type: docs
weight: 30
url: /el/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [IEventListener](../../ieventlistener/)*) {#removeeventlistener}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από το αντικείμενο-στόχο. Εάν ένας [`IEventListener`](../../ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του [`IEventListener`](../../ieventlistener/) που αφαιρείται. |
| listener | IEventListener | Η παράμετρος [`IEventListener`](../../ieventlistener/) υποδεικνύει το [`IEventListener`](../../ieventlistener/) που θα αφαιρεθεί. |

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#removeeventlistener_1}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από το αντικείμενο-στόχο. Εάν ένας [`IEventListener`](../../ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του [`IEventListener`](../../ieventlistener/) που αφαιρείται. |
| listener | IEventListener | Η παράμετρος [`IEventListener`](../../ieventlistener/) υποδεικνύει το [`IEventListener`](../../ieventlistener/) που θα αφαιρεθεί. |
| useCapture | Boolean | Καθορίζει εάν ο EventListener που αφαιρείται είχε καταχωρηθεί ως ακροατής σύλληψης ή όχι. Εάν ένας ακροατής καταχωρηθεί δύο φορές, μία με σύλληψη και μία χωρίς, πρέπει να αφαιρεθούν ξεχωριστά. Η αφαίρεση ενός ακροατή σύλληψης δεν επηρεάζει την έκδοση χωρίς σύλληψη του ίδιου ακροατή, και αντίστροφα. |

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
