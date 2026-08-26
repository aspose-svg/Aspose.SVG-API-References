---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος EventTarget RemoveEventListener. Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο του συμβάντος. Εάν ένας IEventListener αφαιρεθεί από ένα EventTarget ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους"
type: docs
weight: 50
url: /el/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#removeeventlistener}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο του συμβάντος. Εάν ένας [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που αφαιρείται. |
| handler | DOMEventHandler | Η παράμετρος [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) υποδεικνύει τον [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που θα αφαιρεθεί. |
| useCapture | Boolean | Καθορίζει εάν ο EventListener που αφαιρείται είχε καταχωρηθεί ως ακροατής σύλληψης ή όχι. Εάν ένας ακροατής καταχωρηθεί δύο φορές, μία με σύλληψη και μία χωρίς, πρέπει να αφαιρεθούν ξεχωριστά. Η αφαίρεση ενός ακροατή σύλληψης δεν επηρεάζει την έκδοση χωρίς σύλληψη του ίδιου ακροατή, και αντίστροφα. |

### Δείτε επίσης

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#removeeventlistener_1}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο του συμβάντος. Εάν ένας [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που αφαιρείται. |
| listener | IEventListener | Η παράμετρος [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) υποδεικνύει το [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που θα αφαιρεθεί. |

### Δείτε επίσης

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο του συμβάντος. Εάν ένας [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που αφαιρείται. |
| listener | IEventListener | Η παράμετρος [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) υποδεικνύει το [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που θα αφαιρεθεί. |
| useCapture | Boolean | Καθορίζει εάν ο EventListener που αφαιρείται είχε καταχωρηθεί ως ακροατής σύλληψης ή όχι. Εάν ένας ακροατής καταχωρηθεί δύο φορές, μία με σύλληψη και μία χωρίς, πρέπει να αφαιρεθούν ξεχωριστά. Η αφαίρεση ενός ακροατή σύλληψης δεν επηρεάζει την έκδοση χωρίς σύλληψη του ίδιου ακροατή, και αντίστροφα. |

### Δείτε επίσης

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
