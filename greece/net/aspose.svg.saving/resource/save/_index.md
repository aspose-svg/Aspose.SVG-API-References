---
title: "Resource.Save"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Resource Save. Αποθηκεύει τον πόρο στο παρεχόμενο stream."
type: docs
weight: 70
url: /el/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Αποθηκεύει τον πόρο στην παρεχόμενη ροή.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το stream στο οποίο θα αποθηκευτεί ο πόρος. |
| context | ResourceHandlingContext | Πλαίσιο διαχείρισης πόρων. |

### Τιμή Επιστροφής

Αυτός ο πόρος ώστε να μπορείτε να αλυσίδετε κλήσεις.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| InvalidOperationException | Εγείρεται εάν το [`OutputUrl`](../outputurl/) είναι `null`. Το [`OutputUrl`](../outputurl/) πρέπει να καθοριστεί πριν από την αποθήκευση του πόρου, επειδή διαφορετικά είναι αδύνατο να καθοριστεί η σωστή αναφορά στους πόρους που αναφέρονται σε αυτόν. |

### Δείτε επίσης

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
