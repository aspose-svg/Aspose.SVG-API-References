---
title: "Κλάση Metered"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Metered. Παρέχει μεθόδους για τον ορισμό του κλειδιού μετρητή"
type: docs
weight: 4270
url: /el/net/aspose.svg/metered/
---
## Metered class

Παρέχει μεθόδους για τον ορισμό κλειδιού μέτρησης.

```csharp
public class Metered
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Metered](metered/)() | Αρχικοποιεί ένα νέο στιγμιότυπο αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(*string, string*) | Ορίζει το δημόσιο και ιδιωτικό κλειδί του μετρητή. Εάν αγοράσετε άδεια μετρητή, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί· συνήθως αυτό είναι επαρκές. Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση των δεδομένων κατανάλωσης και υπερβεί τις 24 ώρες, η άδεια θα μετατραπεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτή την περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | Λαμβάνει πίστωση κατανάλωσης |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |
| static [IsMeteredLicensed](../../aspose.svg/metered/ismeteredlicensed/)() | Ελέγξτε εάν η μέτρηση είναι αδειοδοτημένη |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το δημόσιο και ιδιωτικό κλειδί της μέτρησης

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

το αρχείο jar του στοιχείου:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Δείτε επίσης

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
