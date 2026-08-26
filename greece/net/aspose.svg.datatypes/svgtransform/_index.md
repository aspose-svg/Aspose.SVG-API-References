---
title: "SVGTransform Class"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.DataTypes.SVGTransform class. Το SVGTransform είναι η διεπαφή για μία από τις μετασχηματιστικές συνιστώσες μέσα σε μια SVGTransformList, έτσι ένα αντικείμενο SVGTransform αντιστοιχεί σε μία μοναδική συνιστώσα π.χ. κλίμακα ή μήτρα μέσα σε μια προδιαγραφή χαρακτηριστικού transform."
type: docs
weight: 2310
url: /el/net/aspose.svg.datatypes/svgtransform/
---
## SVGTransform class

Το SVGTransform είναι το interface για μία από τις μετασχηματιστικές συνιστώσες μέσα σε ένα SVGTransformList· έτσι, ένα αντικείμενο SVGTransform αντιστοιχεί σε μία μόνο συνιστώσα (π.χ., 'scale(…)' ή 'matrix(…)') μέσα σε μια προδιαγραφή του χαρακτηριστικού ‘transform’.

```csharp
public class SVGTransform : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Angle](../../aspose.svg.datatypes/svgtransform/angle/) { get; } | Ένα χαρακτηριστικό ευκολίας για SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX και SVG_TRANSFORM_SKEWY. Κρατά τη γωνία που καθορίστηκε. Για SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE και SVG_TRANSFORM_SCALE, η γωνία θα είναι μηδέν. |
| [Matrix](../../aspose.svg.datatypes/svgtransform/matrix/) { get; } | Ο πίνακας (matrix) που αντιπροσωπεύει αυτή τη μετατροπή. Το αντικείμενο matrix είναι ζωντανό, πράγμα που σημαίνει ότι οποιεσδήποτε αλλαγές γίνουν στο αντικείμενο SVGTransform αντικατοπτρίζονται αμέσως στο αντικείμενο matrix και αντίστροφα. Σε περίπτωση που το αντικείμενο matrix αλλάξει απευθείας (δηλαδή, χωρίς χρήση των μεθόδων στη διεπαφή SVGTransform), τότε ο τύπος του SVGTransform αλλάζει σε SVG_TRANSFORM_MATRIX. Για SVG_TRANSFORM_MATRIX, ο matrix περιέχει τις τιμές a, b, c, d, e, f που παρείχε ο χρήστης. Για SVG_TRANSFORM_TRANSLATE, τα e και f αντιπροσωπεύουν τις ποσότητες μετάφρασης (a=1, b=0, c=0 και d=1). Για SVG_TRANSFORM_SCALE, τα a και d αντιπροσωπεύουν τις ποσότητες κλίμακας (b=0, c=0, e=0 και f=0). Για SVG_TRANSFORM_SKEWX και SVG_TRANSFORM_SKEWY, τα a, b, c και d αντιπροσωπεύουν τον matrix που θα προκύψει από την δεδομένη κλίση (e=0 και f=0). Για SVG_TRANSFORM_ROTATE, τα a, b, c, d, e και f μαζί αντιπροσωπεύουν τον matrix που θα προκύψει από την δεδομένη περιστροφή. Όταν η περιστροφή είναι γύρω από το κεντρικό σημείο (0, 0), τα e και f θα είναι μηδέν. |
| [Type](../../aspose.svg.datatypes/svgtransform/type/) { get; } | Ο τύπος της τιμής όπως καθορίζεται από μία από τις σταθερές SVG_TRANSFORM_* που ορίζονται σε αυτή τη διεπαφή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [SetMatrix](../../aspose.svg.datatypes/svgtransform/setmatrix/)(*[SVGMatrix](../svgmatrix/)*) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_MATRIX, με την παράμετρο matrix που ορίζει τη νέα μετατροπή. Οι τιμές από την παράμετρο matrix αντιγράφονται, η παράμετρος matrix δεν αντικαθιστά το SVGTransform::matrix. |
| [SetRotate](../../aspose.svg.datatypes/svgtransform/setrotate/)(*float, float, float*) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_ROTATE, με την παράμετρο angle που ορίζει τη γωνία περιστροφής και τις παραμέτρους cx και cy που ορίζουν το προαιρετικό κέντρο περιστροφής. |
| [SetScale](../../aspose.svg.datatypes/svgtransform/setscale/)(*float, float*) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_SCALE, με τις παραμέτρους sx και sy που ορίζουν τις ποσότητες κλίμακας. |
| [SetSkewX](../../aspose.svg.datatypes/svgtransform/setskewx/)(*float*) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_SKEWX, με την παράμετρο angle που ορίζει το μέγεθος της κλίσης. |
| [SetSkewY](../../aspose.svg.datatypes/svgtransform/setskewy/)(*float*) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_SKEWY, με την παράμετρο angle που ορίζει το μέγεθος της κλίσης. |
| [SetTranslate](../../aspose.svg.datatypes/svgtransform/settranslate/)(*float, float*) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_TRANSLATE, με τις παραμέτρους tx και ty που ορίζουν τα ποσά μετάφρασης. |
| override [ToString](../../aspose.svg.datatypes/svgtransform/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.svg.datatypes/svgtransform/svg_transform_matrix/) | Ένας μετασχηματισμός 'matrix(…)'. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.svg.datatypes/svgtransform/svg_transform_rotate/) | Ένας μετασχηματισμός 'rotate(…)'. |
| const [SVG_TRANSFORM_SCALE](../../aspose.svg.datatypes/svgtransform/svg_transform_scale/) | Ένας μετασχηματισμός 'scale(…)'. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.svg.datatypes/svgtransform/svg_transform_skewx/) | Ένας μετασχηματισμός 'skewX(…)'. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.svg.datatypes/svgtransform/svg_transform_skewy/) | Ένας μετασχηματισμός 'skewY(…)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.svg.datatypes/svgtransform/svg_transform_translate/) | Ένας μετασχηματισμός 'translate(…)'. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.svg.datatypes/svgtransform/svg_transform_unknown/) | Ο τύπος μονάδας δεν είναι ένας από τους προκαθορισμένους τύπους. Είναι άκυρο να προσπαθήσετε να ορίσετε μια νέα τιμή αυτού του τύπου ή να προσπαθήσετε να αλλάξετε μια υπάρχουσα τιμή σε αυτόν τον τύπο. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
