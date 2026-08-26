---
title: "Κλάση Resource"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Saving.Resource κλάση. Αυτή η κλάση περιγράφει έναν πόρο και παρέχει μεθόδους για την επεξεργασία του"
type: docs
weight: 5710
url: /el/net/aspose.svg.saving/resource/
---
## Resource class

Αυτή η κλάση περιγράφει έναν πόρο και παρέχει μεθόδους για την επεξεργασία του.

```csharp
public class Resource
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Επιστρέφει το !:Html.MimeType αυτού του πόρου. Μπορεί να είναι `null` εάν ο πόρος δεν βρέθηκε. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Επιστρέφει μια συμβολοσειρά που περιέχει την αρχική αναφορά σε αυτόν τον πόρο. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Επιστρέφει ένα URL που υποδεικνύει πού βρισκόταν αυτός ο πόρος. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Λαμβάνει ή ορίζει το URL που υποδεικνύει πού θα βρίσκεται ο πόρος μετά την επεξεργασία. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Επιστρέφει την τρέχουσα κατάσταση του πόρου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Ενσωματώνει αυτόν τον πόρο στο γονικό του κωδικοποιώντας τον ως Base64. Το αποτέλεσμα κωδικοποίησης θα γραφτεί στο [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Αποθηκεύει τον πόρο στην παρεχόμενη ροή. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Καθορίζει το νέο URL που υποδεικνύει πού θα βρίσκεται ο πόρος μετά την επεξεργασία. |

### Δείτε επίσης

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
