---
title: "SVGAngle Κατηγορία"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.DataTypes.SVGAngle κατηγορία. Η διασύνδεση SVGAngle αντιστοιχεί στον βασικό τύπο δεδομένων γωνίας"
type: docs
weight: 2070
url: /el/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

Η διεπαφή SVGAngle αντιστοιχεί στον βασικό τύπο δεδομένων γωνίας.

```csharp
public class SVGAngle : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | Ο τύπος της τιμής όπως ορίζεται από μία από τις σταθερές SVG_ANGLETYPE_* που ορίζονται σε αυτή τη διασύνδεση. |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | Η τιμή της γωνίας ως δεκαδική τιμή, σε μοίρες. Ο καθορισμός αυτού του χαρακτηριστικού θα προκαλέσει την αυτόματη ενημέρωση των valueInSpecifiedUnits και valueAsString ώστε να αντανακλούν αυτή τη ρύθμιση. |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | Η τιμή της γωνίας ως συμβολοσειρά, στις μονάδες που εκφράζονται από το unitType. Ο καθορισμός αυτού του χαρακτηριστικού θα προκαλέσει την αυτόματη ενημέρωση των value, valueInSpecifiedUnits και unitType ώστε να αντανακλούν αυτή τη ρύθμιση. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | Η τιμή της γωνίας ως δεκαδική τιμή, στις μονάδες που εκφράζονται από το unitType. Ο καθορισμός αυτού του χαρακτηριστικού θα προκαλέσει την αυτόματη ενημέρωση των value και valueAsString ώστε να αντανακλούν αυτή τη ρύθμιση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(*ushort*) | Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρετε το αποθηκευμένο αναγνωριστικό μονάδας στο δοσμένο unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString μπορεί να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(*ushort, float*) | Επαναφέρετε την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου. |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | Ο τύπος μονάδας ορίστηκε ρητά σε μοίρες. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | Ο τύπος μονάδας είναι ακτίνια. |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | Ο τύπος μονάδας είναι ακτίνια. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | Ο τύπος μονάδας δεν είναι ένας από τους προκαθορισμένους τύπους μονάδων. Είναι μη έγκυρο να προσπαθήσετε να ορίσετε μια νέα τιμή αυτού του τύπου ή να μεταβείτε από μια υπάρχουσα τιμή σε αυτόν τον τύπο. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | Δεν παρέχεται τύπος μονάδας (δηλαδή, καθορίστηκε τιμή χωρίς μονάδα). Για γωνίες, μια τιμή χωρίς μονάδα αντιμετωπίζεται όπως αν είχαν οριστεί μοίρες. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
