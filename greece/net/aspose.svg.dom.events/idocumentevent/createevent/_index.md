---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "IDocumentEvent CreateEvent method. Δημιουργεί ένα Event τύπου που υποστηρίζεται από την υλοποίηση."
type: docs
weight: 10
url: /el/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Δημιουργεί ένα [`Event`](../../event/) τύπου που υποστηρίζεται από την υλοποίηση.

```csharp
public Event CreateEvent(string eventType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | String | Η παράμετρος eventType καθορίζει τον τύπο της διεπαφής [`Event`](../../event/) που θα δημιουργηθεί. Εάν η καθορισμένη διεπαφή [`Event`](../../event/) υποστηρίζεται από την υλοποίηση, αυτή η μέθοδος θα επιστρέψει ένα νέο [`Event`](../../event/) του ζητούμενου τύπου διεπαφής. Εάν το [`Event`](../../event/) πρόκειται να διανεμηθεί μέσω της μεθόδου [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/), πρέπει να κληθεί η κατάλληλη μέθοδος [`InitEvent`](../../event/initevent/) μετά τη δημιουργία για την αρχικοποίηση των τιμών του [`Event`](../../event/). |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [`Event`](../../event/)

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η υλοποίηση δεν υποστηρίζει τον τύπο της ζητούμενης διεπαφής [`Event`](../../event/) |

### Δείτε επίσης

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
