---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Ιδιότητα SVGSVGElement CurrentScale. Σε ένα εξωτερικό στοιχείο svg, αυτό το χαρακτηριστικό υποδεικνύει τον τρέχοντα συντελεστή κλίμακας σε σχέση με την αρχική προβολή, λαμβάνοντας υπόψη τη μεγέθυνση του χρήστη και τις λειτουργίες μετακίνησης όπως περιγράφονται στην ενότητα Μεγέθυνση και μετακίνηση. Τα χαρακτηριστικά DOM currentScale και currentTranslate είναι ισοδύναμα με τον πίνακα 2x3 a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Εάν η μεγέθυνση είναι ενεργοποιημένη, π.χ. zoomAndPanmagnify, τότε το αποτέλεσμα είναι σαν να τοποθετηθεί μια επιπλέον μετασχηματισμός στο εξωτερικό επίπεδο του τμήματος εγγράφου SVG, δηλαδή εκτός του εξωτερικού στοιχείου svg. Όταν προσπελαστεί σε στοιχείο svg που δεν είναι το εξωτερικό svg στοιχείο, είναι ακαθόριστο το πώς συμπεριφέρεται αυτό το χαρακτηριστικό."
type: docs
weight: 10
url: /el/net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Σε ένα εξωτερικό στοιχείο svg, αυτό το χαρακτηριστικό υποδεικνύει τον τρέχοντα συντελεστή κλίμακας σε σχέση με την αρχική προβολή για να ληφθεί υπόψη η μεγέθυνση και οι λειτουργίες μετακίνησης του χρήστη, όπως περιγράφεται στην Ενότητα Μεγέθυνση και μετακίνηση. Τα χαρακτηριστικά DOM currentScale και currentTranslate είναι ισοδύναμα με τον πίνακα 2x3 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Εάν η «μεγέθυνση» είναι ενεργοποιημένη (π.χ., zoomAndPan=\"magnify\"), τότε το αποτέλεσμα είναι σαν να τοποθετηθεί ένας επιπλέον μετασχηματισμός στο εξωτερικό επίπεδο του τμήματος εγγράφου SVG (δηλαδή, έξω από το εξωτερικό στοιχείο svg). Όταν προσπελαστεί σε ένα στοιχείο ‘svg’ που δεν είναι εξωτερικό στοιχείο svg, είναι ακαθόριστο τι συμπεριφορά έχει αυτό το χαρακτηριστικό.

```csharp
public float CurrentScale { get; set; }
```

### Property Value

Η τρέχουσα κλίμακα.

### Δείτε επίσης

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
