---
title: "License Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.License κλάση. Παρέχει μεθόδους για την αδειοδότηση του στοιχείου."
type: docs
weight: 4260
url: /el/net/aspose.svg/license/
---
## License class

Παρέχει μεθόδους για την αδειοδότηση του στοιχείου.

```csharp
public class License
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [License](license/)() | Αρχικοποιεί ένα νέο στιγμιότυπο αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(*Stream*) | Αδειοδοτεί το στοιχείο. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(*string*) | Αδειοδοτεί το στοιχείο. |

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

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
