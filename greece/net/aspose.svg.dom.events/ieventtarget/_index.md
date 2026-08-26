---
title: "Διεπαφή IEventTarget"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Διεπαφή Aspose.Svg.Dom.Events.IEventTarget. Η διεπαφή EventTarget υλοποιείται από όλους τους Nodes σε μια υλοποίηση που υποστηρίζει το μοντέλο συμβάντων DOM. Συνεπώς, αυτή η διεπαφή μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για binding σε ένα στιγμιότυπο της διεπαφής Node. Η διεπαφή επιτρέπει την καταγραφή και την αφαίρεση των Event Listeners σε ένα EventTarget και την αποστολή συμβάντων σε αυτό το IEventTarget"
type: docs
weight: 2960
url: /el/net/aspose.svg.dom.events/ieventtarget/
---
## IEventTarget interface

Το interface [`EventTarget`](../../aspose.svg.dom/eventtarget/) υλοποιείται από όλους τους Κόμβους σε μια υλοποίηση που υποστηρίζει το Μοντέλο Συμβάντων DOM. Συνεπώς, αυτό το interface μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε μια παρουσία του interface Node. Το interface επιτρέπει την εγγραφή και την αφαίρεση των Ακροατών Συμβάντων σε ένα [`EventTarget`](../../aspose.svg.dom/eventtarget/) και την αποστολή συμβάντων σε αυτό το `IEventTarget`.

```csharp
public interface IEventTarget
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Αυτή η μέθοδος επιτρέπει την εγγραφή ακροατών συμβάντων στον στόχο συμβάντος. |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Αυτή η μέθοδος επιτρέπει την εγγραφή ακροατών συμβάντων στον στόχο συμβάντος. |
| [DispatchEvent](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων της υλοποίησης. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση ακροατών συμβάντων από τον στόχο συμβάντος. Εάν ένα [`IEventListener`](../ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Ακροατές Συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση ακροατών συμβάντων από τον στόχο συμβάντος. Εάν ένα [`IEventListener`](../ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Ακροατές Συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |

### Δείτε επίσης

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
