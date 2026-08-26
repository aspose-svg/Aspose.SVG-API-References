---
title: "License.SetLicense"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος License SetLicense. Εξουσιοδοτεί το στοιχείο."
type: docs
weight: 20
url: /el/net/aspose.svg/license/setlicense/
---
## SetLicense(*string*) {#setlicense_1}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(string licenseName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseName | String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |

## Παρατηρήσεις

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Ρητή διαδρομή.

2. Ο φάκελος που περιέχει το assembly του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το assembly κλήσης του πελάτη.

4. Ο φάκελος που περιέχει το entry (startup) assembly.

5. Ένας ενσωματωμένος πόρος στο assembly κλήσης του πελάτη.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ρητή διαδρομή.

2. Ένας ενσωματωμένος πόρος στο assembly κλήσης του πελάτη.

2. Ο φάκελος που περιέχει το αρχείο JAR του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το αρχείο JAR κλήσης του πελάτη.

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το calling assembly, στον φάκελο του entry assembly και, στη συνέχεια, στους ενσωματωμένους πόρους του calling assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

το αρχείο jar του στοιχείου:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Δείτε επίσης

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SetLicense(*Stream*) {#setlicense}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Μία ροή που περιέχει την άδεια. |

## Παρατηρήσεις

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από μια ροή.

## Παραδείγματα

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Δείτε επίσης

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
