---
title: "SVGLength Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.DataTypes.SVGLength class. Η διεπαφή SVGLength αντιστοιχεί στον βασικό τύπο δεδομένων μήκους. Ένα αντικείμενο SVGLength μπορεί να οριστεί ως μόνο για ανάγνωση, πράγμα που σημαίνει ότι οι προσπάθειες τροποποίησης του αντικειμένου θα προκαλέσουν την εμφάνιση μιας εξαίρεσης όπως περιγράφεται παρακάτω."
type: docs
weight: 2210
url: /el/net/aspose.svg.datatypes/svglength/
---
## SVGLength class

Η διεπαφή SVGLength αντιστοιχεί στον βασικό τύπο δεδομένων length. Ένα αντικείμενο SVGLength μπορεί να οριστεί ως μόνο για ανάγνωση, πράγμα που σημαίνει ότι οι προσπάθειες τροποποίησης του αντικειμένου θα προκαλέσουν την εκκίνηση μιας εξαίρεσης, όπως περιγράφεται παρακάτω.

```csharp
public class SVGLength : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svglength/unittype/) { get; } | Ο τύπος της τιμής όπως καθορίζεται από μία από τις σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτή τη διεπαφή. |
| [Value](../../aspose.svg.datatypes/svglength/value/) { get; set; } | Η τιμή ως αριθμός κινητής υποδιαστολής, σε μονάδες χρήστη. Η ρύθμιση αυτής της ιδιότητας θα προκαλέσει την αυτόματη ενημέρωση των valueInSpecifiedUnits και valueAsString ώστε να αντικατοπτρίζουν αυτή τη ρύθμιση. |
| [ValueAsString](../../aspose.svg.datatypes/svglength/valueasstring/) { get; set; } | Η τιμή ως συμβολοσειρά, στις μονάδες που εκφράζονται από το unitType. Η ρύθμιση αυτής της ιδιότητας θα προκαλέσει την αυτόματη ενημέρωση των value, valueInSpecifiedUnits και unitType ώστε να αντικατοπτρίζουν αυτή τη ρύθμιση. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | Η τιμή ως αριθμός κινητής υποδιαστολής, στις μονάδες που εκφράζονται από το unitType. Η ρύθμιση αυτής της ιδιότητας θα προκαλέσει την αυτόματη ενημέρωση των value και valueAsString ώστε να αντικατοπτρίζουν αυτή τη ρύθμιση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svglength/converttospecifiedunits/)(*ushort*) | Διατηρεί την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρει το αποθηκευμένο αναγνωριστικό μονάδας στο δοσμένο unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα, εάν η αρχική τιμή ήταν "0.5cm" και η μέθοδος κληθεί για μετατροπή σε χιλιοστά, τότε το unitType θα αλλάξει σε SVG_LENGTHTYPE_MM, το valueInSpecifiedUnits θα αλλάξει στην αριθμητική τιμή 5 και το valueAsString θα αλλάξει σε "5mm". |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svglength/newvaluespecifiedunits/)(*ushort, float*) | Επαναφέρετε την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου. |
| override [ToString](../../aspose.svg.datatypes/svglength/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.svg.datatypes/svglength/svg_lengthtype_cm/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες cm που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.svg.datatypes/svglength/svg_lengthtype_ems/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες em που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.svg.datatypes/svglength/svg_lengthtype_exs/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες ex που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.svg.datatypes/svglength/svg_lengthtype_in/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες in που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.svg.datatypes/svglength/svg_lengthtype_mm/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες mm που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.svg.datatypes/svglength/svg_lengthtype_number/) | Δεν παρέχεται τύπος μονάδας (δηλαδή, καθορίστηκε τιμή χωρίς μονάδα), που υποδεικνύει τιμή σε μονάδες χρήστη. |
| const [SVG_LENGTHTYPE_PC](../../aspose.svg.datatypes/svglength/svg_lengthtype_pc/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες pc που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.svg.datatypes/svglength/svg_lengthtype_percentage/) | Καθορίστηκε τιμή ποσοστού. |
| const [SVG_LENGTHTYPE_PT](../../aspose.svg.datatypes/svglength/svg_lengthtype_pt/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες pt που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.svg.datatypes/svglength/svg_lengthtype_px/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες px που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.svg.datatypes/svglength/svg_lengthtype_unknown/) | Ο τύπος μονάδας δεν είναι ένας από τους προκαθορισμένους τύπους μονάδων. Είναι μη έγκυρο να προσπαθήσετε να ορίσετε μια νέα τιμή αυτού του τύπου ή να μεταβείτε από μια υπάρχουσα τιμή σε αυτόν τον τύπο. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
