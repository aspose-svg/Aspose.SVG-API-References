---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος MatchFontFallback του FontMatcher. Αυτή η μέθοδος καλείται εάν δεν βρεθεί κατάλληλη γραμματοσειρά στους φακέλους αναζήτησης γραμματοσειρών. Θα πρέπει να επιστρέφει μια γραμματοσειρά true type βάσει των fontMatchingProperties που μπορεί να αποδώσει το charCode ή `null` εάν τέτοια γραμματοσειρά δεν είναι διαθέσιμη."
type: docs
weight: 10
url: /el/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Αυτή η μέθοδος καλείται εάν δεν βρεθεί κατάλληλη γραμματοσειρά στους φακέλους αναζήτησης γραμματοσειρών. Θα πρέπει να επιστρέφει γραμματοσειρά τύπου true βάσει των *fontMatchingProperties* που μπορεί να αποδώσει *charCode*, ή `null` εάν τέτοια γραμματοσειρά δεν είναι διαθέσιμη.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    int charCode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Ιδιότητες της αντιστοιχισμένης γραμματοσειράς. |
| charCode | Int32 | Κώδικας του χαρακτήρα που θα αποδοθεί χρησιμοποιώντας την αντιστοιχισμένη γραμματοσειρά. |

### Τιμή Επιστροφής

Ένας πίνακας byte που περιέχει τα δεδομένα των γραμματοσειρών ή `null`.

### Δείτε επίσης

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
