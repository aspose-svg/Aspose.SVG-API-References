---
title: "SVGTransform.Matrix"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGTransform Matrix property. Ο matrix που αντιπροσωπεύει αυτόν τον μετασχηματισμό. Το αντικείμενο matrix είναι ενεργό, πράγμα που σημαίνει ότι οποιεσδήποτε αλλαγές γίνουν στο αντικείμενο SVGTransform αντικατοπτρίζονται αμέσως στο αντικείμενο matrix και αντίστροφα. Σε περίπτωση που το αντικείμενο matrix αλλάξει άμεσα, δηλαδή χωρίς χρήση των μεθόδων στο interface SVGTransform, τότε ο τύπος του SVGTransform αλλάζει σε SVG_TRANSFORM_MATRIX. Για SVG_TRANSFORM_MATRIX ο matrix περιέχει τις τιμές a b c d e f που παρέχονται από τον χρήστη. Για SVG_TRANSFORM_TRANSLATE τα e και f αντιπροσωπεύουν το ποσό μετάφρασης a 1 b 0 c 0 και d  1. Για SVG_TRANSFORM_SCALE τα a και d αντιπροσωπεύουν τα ποσά κλίμακας b 0 c 0 e 0 και f  0. Για SVG_TRANSFORM_SKEWX και SVG_TRANSFORM_SKEWY τα a b c και d αντιπροσωπεύουν τον matrix που θα οδηγήσει στην δεδομένη παραμόρφωση 0 και f  0. Για SVG_TRANSFORM_ROTATE τα a b c d e και f μαζί αντιπροσωπεύουν τον matrix που θα οδηγήσει στην δεδομένη περιστροφή. Όταν η περιστροφή είναι γύρω από το κεντρικό σημείο 0 0, τα e και f θα είναι μηδέν."
type: docs
weight: 20
url: /el/net/aspose.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Ο πίνακας (matrix) που αντιπροσωπεύει αυτή τη μετατροπή. Το αντικείμενο matrix είναι ζωντανό, πράγμα που σημαίνει ότι οποιεσδήποτε αλλαγές γίνουν στο αντικείμενο SVGTransform αντικατοπτρίζονται αμέσως στο αντικείμενο matrix και αντίστροφα. Σε περίπτωση που το αντικείμενο matrix αλλάξει απευθείας (δηλαδή, χωρίς χρήση των μεθόδων στη διεπαφή SVGTransform), τότε ο τύπος του SVGTransform αλλάζει σε SVG_TRANSFORM_MATRIX. Για SVG_TRANSFORM_MATRIX, ο matrix περιέχει τις τιμές a, b, c, d, e, f που παρείχε ο χρήστης. Για SVG_TRANSFORM_TRANSLATE, τα e και f αντιπροσωπεύουν τις ποσότητες μετάφρασης (a=1, b=0, c=0 και d=1). Για SVG_TRANSFORM_SCALE, τα a και d αντιπροσωπεύουν τις ποσότητες κλίμακας (b=0, c=0, e=0 και f=0). Για SVG_TRANSFORM_SKEWX και SVG_TRANSFORM_SKEWY, τα a, b, c και d αντιπροσωπεύουν τον matrix που θα προκύψει από την δεδομένη κλίση (e=0 και f=0). Για SVG_TRANSFORM_ROTATE, τα a, b, c, d, e και f μαζί αντιπροσωπεύουν τον matrix που θα προκύψει από την δεδομένη περιστροφή. Όταν η περιστροφή είναι γύρω από το κεντρικό σημείο (0, 0), τα e και f θα είναι μηδέν.

```csharp
public SVGMatrix Matrix { get; }
```

### Property Value

Ο matrix που αντιπροσωπεύει αυτόν τον μετασχηματισμό.

### Δείτε επίσης

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
