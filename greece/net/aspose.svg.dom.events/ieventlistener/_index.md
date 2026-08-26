---
title: "IEventListener Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Events.IEventListener διεπαφή. Η διεπαφή IEventListener είναι η κύρια μέθοδος για τη διαχείριση γεγονότων. Οι χρήστες υλοποιούν τη διεπαφή IEventListener και καταχωρούν τον ακροατή τους σε ένα EventTarget χρησιμοποιώντας τη μέθοδο AddEventListener. Οι χρήστες πρέπει επίσης να αφαιρέσουν το IEventListener τους από το EventTarget του μετά την ολοκλήρωση της χρήσης του ακροατή."
type: docs
weight: 2950
url: /el/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

Η διεπαφή `IEventListener` είναι η κύρια μέθοδος για τη διαχείριση γεγονότων. Οι χρήστες υλοποιούν τη διεπαφή `IEventListener` και καταχωρούν τον ακροατή τους σε ένα [`EventTarget`](../../aspose.svg.dom/eventtarget/) χρησιμοποιώντας τη μέθοδο [`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener/). Οι χρήστες πρέπει επίσης να αφαιρέσουν το `IEventListener` τους από το αντίστοιχο [`EventTarget`](../../aspose.svg.dom/eventtarget/) μετά την ολοκλήρωση της χρήσης του ακροατή.

```csharp
public interface IEventListener
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent/)(*[Event](../event/)*) | Αυτή η μέθοδος καλείται όποτε συμβαίνει ένα γεγονός του τύπου για τον οποίο η διεπαφή `IEventListener` έχει καταχωρηθεί. |

## Παρατηρήσεις

Όταν ένας Node αντιγράφεται χρησιμοποιώντας τη μέθοδο cloneNode, οι ακροατές γεγονότων που είναι συνδεδεμένοι στον πηγαίο Node δεν συνδέονται στον αντίγραφο Node. Εάν ο χρήστης επιθυμεί οι ίδιοι ακροατές γεγονότων να προστεθούν στο νεοδημιουργημένο αντίγραφο, ο χρήστης πρέπει να τους προσθέσει χειροκίνητα.

### Δείτε επίσης

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
