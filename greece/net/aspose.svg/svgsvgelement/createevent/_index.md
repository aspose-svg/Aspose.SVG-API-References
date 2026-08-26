---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGSVGElement CreateEvent. Δημιουργεί ένα Event τύπου που υποστηρίζεται από την υλοποίηση."
type: docs
weight: 110
url: /el/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Δημιουργεί ένα [`Event`](../../../aspose.svg.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση.

```csharp
public Event CreateEvent(string eventType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | String | Η παράμετρος eventType καθορίζει τον τύπο της διεπαφής [`Event`](../../../aspose.svg.dom.events/event/) που θα δημιουργηθεί. Εάν η διεπαφή [`Event`](../../../aspose.svg.dom.events/event/) που καθορίζεται υποστηρίζεται από την υλοποίηση, αυτή η μέθοδος θα επιστρέψει ένα νέο [`Event`](../../../aspose.svg.dom.events/event/) του ζητούμενου τύπου διεπαφής. Εάν το [`Event`](../../../aspose.svg.dom.events/event/) πρόκειται να διανεμηθεί μέσω της μεθόδου [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/), πρέπει να κληθεί η κατάλληλη μέθοδος [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) μετά τη δημιουργία, προκειμένου να αρχικοποιηθούν οι τιμές του [`Event`](../../../aspose.svg.dom.events/event/). |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [`Event`](../../../aspose.svg.dom.events/event/)

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η υλοποίηση δεν υποστηρίζει τον τύπο της ζητούμενης διεπαφής [`Event`](../../../aspose.svg.dom.events/event/) |

### Δείτε επίσης

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
