---
title: "Color Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Drawing.Color κλάση. Η κλάση Color σας επιτρέπει να καθορίζετε χρώματα ως τιμές Red-Green-Blue RGB, τιμές Hue-Saturation-Luminosity HSL, τιμές Hue-Saturation-Value HSV, τιμές Hue-Whiteness-Blackness HWB, τιμές lightness-A-B LAB, τιμές Luminance-Chroma-Hue LCH, τιμές Cyan-Magenta-Yellow-Key CMYK, φυσικά χρώματα NCOL ή με όνομα χρώματος. Ένα κανάλι Alpha είναι επίσης διαθέσιμο για να υποδεικνύει τη διαφάνεια."
type: docs
weight: 3390
url: /el/net/aspose.svg.drawing/color/
---
## Color class

Η κλάση Color σας επιτρέπει να καθορίζετε χρώματα ως τιμές Red-Green-Blue (RGB), Hue-Saturation-Luminosity (HSL), Hue-Saturation-Value (HSV), Hue-Whiteness-Blackness (HWB), lightness-A-B (LAB), Luminance-Chroma-Hue (LCH), Cyan-Magenta-Yellow-Key (CMYK), Natural colors (NCOL) ή με όνομα χρώματος. Ένα κανάλι Alpha είναι επίσης διαθέσιμο για να υποδεικνύει τη διαφάνεια.

```csharp
public class Color
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Color](color/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Από προεπιλογή, το χρώμα είναι μαύρο. |
| [Color](color/#constructor_1)(*byte, byte, byte*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά του χρώματος πρέπει να βρίσκονται στο εύρος 0-255. |
| [Color](color/#constructor_5)(*float, float, float*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά του χρώματος πρέπει να βρίσκονται στο εύρος 0-1. |
| [Color](color/#constructor_3)(*int, int, int*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά του χρώματος πρέπει να βρίσκονται στο εύρος 0-255. |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά του χρώματος πρέπει να βρίσκονται στο εύρος 0-255. |
| [Color](color/#constructor_6)(*float, float, float, float*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά του χρώματος πρέπει να βρίσκονται στο εύρος 0-1. |
| [Color](color/#constructor_4)(*int, int, int, int*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά του χρώματος πρέπει να βρίσκονται στο εύρος 0-255. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Alpha](../../aspose.svg.drawing/color/alpha/) { get; } | Αντιπροσωπεύει το συστατικό άλφα του χρώματος. |
| [Blue](../../aspose.svg.drawing/color/blue/) { get; } | Αντιπροσωπεύει το μπλε συστατικό του χρώματος. |
| [Green](../../aspose.svg.drawing/color/green/) { get; } | Αντιπροσωπεύει το πράσινο συστατικό του χρώματος. |
| [Red](../../aspose.svg.drawing/color/red/) { get; } | Αντιπροσωπεύει το κόκκινο συστατικό του χρώματος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromCmyk](../../aspose.svg.drawing/color/fromcmyk/)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές κυανό, ματζέντα, κίτρινο, key (μαύρο). |
| static [FromCmyka](../../aspose.svg.drawing/color/fromcmyka/)(*float, float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές κυανό, ματζέντα, κίτρινο, key (μαύρο), άλφα. |
| static [FromGray](../../aspose.svg.drawing/color/fromgray/)(*float*) | Επιστρέφει ένα νέο Χρώμα με τη ζητούμενη τιμή γκρι. |
| static [FromHsl](../../aspose.svg.drawing/color/fromhsl/)(*float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές απόχρωση, κορεσμός, κορεσμός. |
| static [FromHsla](../../aspose.svg.drawing/color/fromhsla/)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές απόχρωση, κορεσμός, κορεσμός, άλφα. |
| static [FromHsv](../../aspose.svg.drawing/color/fromhsv/)(*float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές απόχρωση, κορεσμός, τιμή. |
| static [FromHsva](../../aspose.svg.drawing/color/fromhsva/)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές απόχρωση, κορεσμός, τιμή, άλφα. |
| static [FromHwb](../../aspose.svg.drawing/color/fromhwb/)(*float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές απόχρωση, λευκότητα, μαυρότητα. |
| static [FromHwba](../../aspose.svg.drawing/color/fromhwba/)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές απόχρωση, λευκότητα, μαυρότητα. |
| static [FromInt](../../aspose.svg.drawing/color/fromint/)(*int*) | Επιστρέφει ένα νέο Χρώμα με τη ζητούμενη τιμή ARGB. |
| static [FromLab](../../aspose.svg.drawing/color/fromlab/)(*float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές φωτεινότητα, A, B. |
| static [FromLaba](../../aspose.svg.drawing/color/fromlaba/)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές φωτεινότητα, A, B, άλφα. |
| static [FromLch](../../aspose.svg.drawing/color/fromlch/)(*float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές λαμπρότητα, χρωματική, απόχρωση. |
| static [FromLcha](../../aspose.svg.drawing/color/fromlcha/)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές λαμπρότητα, χρωματική, απόχρωση, άλφα. |
| static [FromOklab](../../aspose.svg.drawing/color/fromoklab/)(*float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές φωτεινότητα, A, B για το μοντέλο OKLAB. |
| static [FromOklaba](../../aspose.svg.drawing/color/fromoklaba/)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές φωτεινότητα, A, B, άλφα για το μοντέλο OKLAB. |
| static [FromOklch](../../aspose.svg.drawing/color/fromoklch/)(*float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές λαμπρότητα, χρωματική, απόχρωση για το μοντέλο OKLAB. |
| static [FromOklcha](../../aspose.svg.drawing/color/fromoklcha/)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές λαμπρότητα, χρωματική, απόχρωση, άλφα για το μοντέλο OKLAB. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-255. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-1. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-255. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε, άλφα. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-255. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε, άλφα. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-1. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | Επιστρέφει ένα νέο Χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε, άλφα. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-255. |
| static [FromString](../../aspose.svg.drawing/color/fromstring/)(*string*) | Αναλύει τη συμβολοσειρά που περιέχει το χρώμα CSS και επιστρέφει ένα νέο Χρώμα. |
| static [FromUint](../../aspose.svg.drawing/color/fromuint/)(*uint*) | Επιστρέφει ένα νέο Χρώμα με τη ζητούμενη τιμή ARGB. |
| [AddLuminosity](../../aspose.svg.drawing/color/addluminosity/)(*float*) | Δημιουργεί αντίγραφο του Χρώματος με το άθροισμα της φωτεινότητάς του και της τιμής delta. |
| [Convert](../../aspose.svg.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | Επιστρέφει τα συστατικά χρώματος στη μορφή του καθορισμένου μοντέλου χρώματος. |
| override [Equals](../../aspose.svg.drawing/color/equals/)(*object*) | Καθορίζει εάν το καθορισμένο `Color` είναι ίσο με αυτήν την παρουσία. |
| [GetComplementary](../../aspose.svg.drawing/color/getcomplementary/)() | Επιστρέφει ένα νέο χρώμα που βρίσκεται στην αντίθετη πλευρά του χρωματικού κύκλου από το αρχικό. |
| override [GetHashCode](../../aspose.svg.drawing/color/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού. |
| [GetHue](../../aspose.svg.drawing/color/gethue/)() | Επιστρέφει το Hue του Color. |
| [GetLuminosity](../../aspose.svg.drawing/color/getluminosity/)() | Επιστρέφει τη φωτεινότητα του Color. |
| [GetSaturation](../../aspose.svg.drawing/color/getsaturation/)() | Επιστρέφει τον κορεσμό του Color. |
| [ToInt](../../aspose.svg.drawing/color/toint/)() | Κωδικοποιεί τα συστατικά ARGB του Color σε int. |
| [ToName](../../aspose.svg.drawing/color/toname/)() | Επιστρέφει το όνομα του χρώματος εάν ταιριάζει με χρώμα στη λίστα των ονομαστικών χρωμάτων CSS, ή μια κενή συμβολοσειρά. |
| [ToNaturalColorString](../../aspose.svg.drawing/color/tonaturalcolorstring/)(*int*) | Επιστρέφει ένα χρώμα Natural colors (NCol) που καθορίζεται χρησιμοποιώντας ένα γράμμα χρώματος με έναν αριθμό για τον καθορισμό της απόστασης (σε ποσοστό) από το χρώμα. |
| [ToRgbaHexString](../../aspose.svg.drawing/color/torgbahexstring/)() | Επιστρέφει ένα δεκαεξαδικό χρώμα που ορίζεται με: #RRGGBBAA. |
| [ToRgbaString](../../aspose.svg.drawing/color/torgbastring/)() | Επιστρέφει μια συμβολοσειρά που περιέχει το χρώμα RGBA που ορίζεται από: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.svg.drawing/color/torgbhexstring/)() | Επιστρέφει ένα δεκαεξαδικό χρώμα που ορίζεται με: #RRGGBB. |
| [ToRgbString](../../aspose.svg.drawing/color/torgbstring/)() | Επιστρέφει μια συμβολοσειρά που περιέχει το χρώμα RGB που ορίζεται από: rgb(R, G, B). |
| override [ToString](../../aspose.svg.drawing/color/tostring/)() | Επιστρέφει μια συμβολοσειρά που αποτελείται από τις τιμές των συστατικών RGBA. |
| [ToUint](../../aspose.svg.drawing/color/touint/)() | Κωδικοποιεί τα συστατικά ARGB του Color σε unsigned int. |
| [WithAlpha](../../aspose.svg.drawing/color/withalpha/)(*float*) | Δημιουργεί αντίγραφο του Color με το καθορισμένο συστατικό alpha. |
| [WithHue](../../aspose.svg.drawing/color/withhue/)(*float*) | Δημιουργεί αντίγραφο του Color με το καθορισμένο Hue. |
| [WithLuminosity](../../aspose.svg.drawing/color/withluminosity/)(*float*) | Δημιουργεί αντίγραφο του Color με την καθορισμένη φωτεινότητα. |
| [WithSaturation](../../aspose.svg.drawing/color/withsaturation/)(*float*) | Δημιουργεί αντίγραφο του Color με τον καθορισμένο κορεσμό. |

### Δείτε επίσης

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
