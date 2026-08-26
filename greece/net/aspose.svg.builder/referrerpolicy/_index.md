---
title: "ReferrerPolicy Enum"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Καθορίζει την πολιτική referrer που θα χρησιμοποιηθεί κατά την ανάκτηση πόρων"
type: docs
weight: 1020
url: /el/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Καθορίζει την πολιτική παραπομπής που θα χρησιμοποιηθεί κατά την ανάκτηση πόρων.

```csharp
public enum ReferrerPolicy
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | `0` | Δεν έχει οριστεί πολιτική referrer. |
| NoReferrer | `1` | Η κεφαλίδα Referer δεν θα αποσταλεί. |
| NoReferrerWhenDowngrade | `2` | Η κεφαλίδα Referer δεν θα αποσταλεί σε προελεύσεις με λιγότερη ασφάλεια (HTTPS -> HTTP). |
| SameOrigin | `3` | Η κεφαλίδα Referer θα αποστέλλεται μόνο για αιτήματα ίδιας προέλευσης. |
| Origin | `4` | Μόνο η προέλευση του εγγράφου θα αποστέλλεται ως κεφαλίδα Referer. |
| StrictOrigin | `5` | Μόνο η προέλευση του εγγράφου θα αποστέλλεται ως κεφαλίδα Referer για ασφαλή περιβάλλοντα. |
| OriginWhenCrossOrigin | `6` | Η πλήρης διεύθυνση URL θα αποστέλλεται ως κεφαλίδα Referer για αιτήματα ίδιας προέλευσης, αλλά μόνο η προέλευση για αιτήματα διαφορετικής προέλευσης. |
| StrictOriginWhenCrossOrigin | `7` | Μόνο η προέλευση του εγγράφου θα αποστέλλεται ως κεφαλίδα Referer για αιτήματα ίδιας προέλευσης, αλλά δεν θα αποστέλλεται κεφαλίδα για αιτήματα διαφορετικής προέλευσης σε μη ασφαλή περιβάλλοντα. |
| UnsafeUrl | `8` | Η πλήρης διεύθυνση URL, συμπεριλαμβανομένου του μονοπατιού και της αλφαριθμητικής συμβολοσειράς ερωτήματος, θα αποστέλλεται πάντα ως κεφαλίδα Referer. |

### Δείτε επίσης

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
