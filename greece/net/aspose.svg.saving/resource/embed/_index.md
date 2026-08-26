---
title: "Resource.Embed"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Resource Embed. Ενσωματώνει αυτόν τον πόρο μέσα στον γονέα του κωδικοποιώντας τον ως Base64. Το αποτέλεσμα της κωδικοποίησης θα γραφτεί στο OutputUrl."
type: docs
weight: 60
url: /el/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Ενσωματώνει αυτόν τον πόρο μέσα στον γονέα του κωδικοποιώντας τον ως Base64. Το αποτέλεσμα της κωδικοποίησης θα γραφτεί στο [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| context | ResourceHandlingContext | Πλαίσιο διαχείρισης πόρων. |

### Τιμή Επιστροφής

Αυτός ο πόρος ώστε να μπορείτε να αλυσίδετε κλήσεις.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| InvalidOperationException | Εγείρεται εάν δεν υπάρχει [`ParentResource`](../../resourcehandlingcontext/parentresource/) επειδή δεν υπάρχει που να ενσωματωθεί το αποτέλεσμα. |

### Δείτε επίσης

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
