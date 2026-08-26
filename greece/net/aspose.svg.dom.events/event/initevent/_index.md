---
title: "Event.InitEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Event InitEvent. Η μέθοδος InitEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός Event που δημιουργείται μέσω της διεπαφής IDocumentEvent."
type: docs
weight: 110
url: /el/net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

Η μέθοδος `InitEvent` χρησιμοποιείται για την αρχικοποίηση της τιμής ενός [`Event`](../) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../../idocumentevent/).

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος του γεγονότος. |
| bubbles | Boolean | αν οριστεί σε `true` [bubbles]. |
| cancelable | Boolean | αν οριστεί σε `true` [cancelable]. |

## Παρατηρήσεις

Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το Event έχει αποσταλεί μέσω της μεθόδου [`DispatchEvent`](../../ieventtarget/dispatchevent/), αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλές φορές, η τελική κλήση έχει προτεραιότητα. Εάν κληθεί από μια υποκλάση της διεπαφής Event, μόνο οι τιμές που καθορίζονται στη μέθοδο initEvent τροποποιούνται, όλα τα άλλα χαρακτηριστικά παραμένουν αμετάβλητα.

### Δείτε επίσης

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
