---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος InitTimeEvent του TimeEvent. Η μέθοδος initTimeEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός TimeEvent που δημιουργήθηκε μέσω της διεπαφής DocumentEvent. Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το TimeEvent διανεμηθεί μέσω της μεθόδου dispatchEvent, αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλές φορές, η τελική κλήση έχει προτεραιότητα."
type: docs
weight: 30
url: /el/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Η μέθοδος initTimeEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός TimeEvent που δημιουργείται μέσω της διεπαφής DocumentEvent. Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το TimeEvent αποσταλεί μέσω της μεθόδου dispatchEvent, αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλές φορές, η τελική κλήση έχει προτεραιότητα.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeArg | String | Καθορίζει τον τύπο του συμβάντος. |
| viewArg | IAbstractView | Καθορίζει το AbstractView του Event. |
| detailArg | Int64 | Καθορίζει τη λεπτομέρεια του Event. |

### Δείτε επίσης

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
