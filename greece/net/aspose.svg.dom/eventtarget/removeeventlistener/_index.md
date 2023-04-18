---
title: EventTarget.RemoveEventListener
second_title: Aspose.SVG για Αναφορά API .NET
description: EventTarget μέθοδος. Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. ΕάνIEventListener αφαιρείται από έναEventTarget ενώ επεξεργάζεται ένα συμβάν δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση.
type: docs
weight: 40
url: /el/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) αφαιρείται από ένα[`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που αφαιρείται. |
| handler | DOMEventHandler | ο[`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) παράμετρος δείχνει το[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) να αφαιρεθεί. |
| useCapture | Boolean | Καθορίζει εάν το EventListener που καταργείται έχει καταχωρηθεί ως ακροατής λήψης ή όχι. Εάν ένας ακροατής έχει εγγραφεί δύο φορές, ένας με καταγραφή και ένας χωρίς, το καθένα πρέπει να αφαιρεθεί ξεχωριστά. Η αφαίρεση ενός ακροατή που καταγράφει δεν επηρεάζει την έκδοση που δεν καταγράφει του ίδιου ακροατή, και αντίστροφα. |

### Δείτε επίσης

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* χώρος ονομάτων [Aspose.Svg.Dom](../../eventtarget/)
* συνέλευση [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) αφαιρείται από ένα[`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που αφαιρείται. |
| listener | IEventListener | ο[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) παράμετρος δείχνει το[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) να αφαιρεθεί. |

### Δείτε επίσης

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* χώρος ονομάτων [Aspose.Svg.Dom](../../eventtarget/)
* συνέλευση [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) αφαιρείται από ένα[`EventTarget`](../) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) που αφαιρείται. |
| listener | IEventListener | ο[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) παράμετρος δείχνει το[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) να αφαιρεθεί. |
| useCapture | Boolean | Καθορίζει εάν το EventListener που καταργείται έχει καταχωρηθεί ως ακροατής λήψης ή όχι. Εάν ένας ακροατής έχει εγγραφεί δύο φορές, ένας με καταγραφή και ένας χωρίς, το καθένα πρέπει να αφαιρεθεί ξεχωριστά. Η αφαίρεση ενός ακροατή που καταγράφει δεν επηρεάζει την έκδοση που δεν καταγράφει του ίδιου ακροατή, και αντίστροφα. |

### Δείτε επίσης

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* χώρος ονομάτων [Aspose.Svg.Dom](../../eventtarget/)
* συνέλευση [Aspose.SVG](../../../)


