---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος ResourceHandler HandleResourceReference. Αυτή η μέθοδος είναι υπεύθυνη για τη διαχείριση της παραπομπής πόρου. Σε αυτήν τη μέθοδο μπορείτε να ορίσετε πώς θα φαίνεται η παραπομπή στον πόρο που διαχειρίζεται."
type: docs
weight: 20
url: /el/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Αυτή η μέθοδος είναι υπεύθυνη για τη διαχείριση της αναφοράς του πόρου. Σε αυτή τη μέθοδο, μπορείτε να ορίσετε πώς θα φαίνεται η αναφορά στον πόρο που διαχειρίζεται.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resource | Resource | Το [`Resource`](../../../aspose.svg.saving/resource/) που θα διαχειριστείται. |
| context | ResourceHandlingContext | Πλαίσιο διαχείρισης πόρων. |

### Τιμή Επιστροφής

Μια συμβολοσειρά που θα γραφτεί στον γονικό πόρο και που αντιπροσωπεύει μια παραπομπή στον πόρο που διαχειρίζεται αυτή τη στιγμή.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| InvalidOperationException | Εγείρεται εάν το [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) είναι `null` και το [`Status`](../../../aspose.svg.saving/resource/status/) είναι Saved. Το [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) πρέπει να καθοριστεί για αποθηκευμένο πόρο, επειδή διαφορετικά είναι αδύνατο να καθοριστεί η σωστή παραπομπή στους πόρους που αναφέρονται σε αυτόν. |

### Δείτε επίσης

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
