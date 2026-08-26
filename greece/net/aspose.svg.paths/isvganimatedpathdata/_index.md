---
title: "ISVGAnimatedPathData Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Paths.ISVGAnimatedPathData διεπαφή. Η διεπαφή SVGAnimatedPathData υποστηρίζει στοιχεία που έχουν χαρακτηριστικό d που περιέχει δεδομένα διαδρομής SVG και υποστηρίζει τη δυνατότητα κίνησης αυτού του χαρακτηριστικού."
type: docs
weight: 4550
url: /el/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Η διεπαφή SVGAnimatedPathData υποστηρίζει στοιχεία που έχουν ένα χαρακτηριστικό ‘d’ που περιέχει δεδομένα διαδρομής SVG και υποστηρίζει τη δυνατότητα animation αυτού του χαρακτηριστικού.

```csharp
public interface ISVGAnimatedPathData
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Παρέχει πρόσβαση στα τρέχοντα κινούμενα περιεχόμενα του χαρακτηριστικού ‘d’ με μορφή που ταιριάζει ακριβώς με τη σύνταξη του SVG. Εάν το συγκεκριμένο χαρακτηριστικό ή ιδιότητα βρίσκεται σε κίνηση, περιέχει την τρέχουσα τιμή κίνησης του χαρακτηριστικού ή της ιδιότητας, και τόσο το αντικείμενο όσο και τα περιεχόμενά του είναι μόνο για ανάγνωση. Εάν το συγκεκριμένο χαρακτηριστικό ή ιδιότητα δεν βρίσκεται σε κίνηση, περιέχει την ίδια τιμή με το pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Παρέχει πρόσβαση στα βασικά (δηλαδή στατικά) περιεχόμενα του χαρακτηριστικού ‘d’ με μορφή που ταιριάζει ακριβώς με τη σύνταξη του SVG. Έτσι, εάν το χαρακτηριστικό ‘d’ περιέχει μια «απόλυτη εντολή μετακίνησης (M)» και μια «απόλυτη εντολή τόξου (A)», τότε το pathSegList θα έχει δύο καταχωρήσεις: ένα SVG_PATHSEG_MOVETO_ABS και ένα SVG_PATHSEG_ARC_ABS. |

### Δείτε επίσης

* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
