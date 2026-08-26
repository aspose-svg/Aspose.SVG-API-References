---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "CustomEvent InitCustomEvent μέθοδος. /// Η μέθοδος InitEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός Event που δημιουργείται μέσω της διεπαφής IDocumentEvent"
type: docs
weight: 30
url: /el/net/aspose.svg.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Η μέθοδος [`InitEvent`](../../event/initevent/) χρησιμοποιείται για την αρχικοποίηση της τιμής ενός [`Event`](../../event/) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../../idocumentevent/).

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος του γεγονότος. |
| bubbles | Boolean | αν οριστεί σε `true` [bubbles]. |
| cancelable | Boolean | αν οριστεί σε `true` [cancelable]. |
| detail | Αντικείμενο | Τα προσαρμοσμένα δεδομένα. |

## Παρατηρήσεις

Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το Event έχει αποσταλεί μέσω της μεθόδου [`DispatchEvent`](../../ieventtarget/dispatchevent/), αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλές φορές, η τελική κλήση έχει προτεραιότητα. Εάν κληθεί από μια υποκλάση της διεπαφής Event, μόνο οι τιμές που καθορίζονται στη μέθοδο initEvent τροποποιούνται, όλα τα άλλα χαρακτηριστικά παραμένουν αμετάβλητα.

### Δείτε επίσης

* class [CustomEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
