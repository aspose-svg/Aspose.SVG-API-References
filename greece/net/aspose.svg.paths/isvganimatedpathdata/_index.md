---
title: Interface ISVGAnimatedPathData
second_title: Aspose.SVG για Αναφορά API .NET
description: Aspose.Svg.Paths.ISVGAnimatedPathData διεπαφή. η διεπαφή SVGAnimatedPathData υποστηρίζει στοιχεία που έχουν ένα χαρακτηριστικό d που περιέχει δεδομένα διαδρομής SVG και υποστηρίζει τη δυνατότητα κίνησης αυτού του χαρακτηριστικού.
type: docs
weight: 2480
url: /el/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

η διεπαφή SVGAnimatedPathData υποστηρίζει στοιχεία που έχουν ένα χαρακτηριστικό "d" που περιέχει δεδομένα διαδρομής SVG και υποστηρίζει τη δυνατότητα κίνησης αυτού του χαρακτηριστικού.

```csharp
public interface ISVGAnimatedPathData
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Παρέχει πρόσβαση στο τρέχον κινούμενο περιεχόμενο του χαρακτηριστικού 'd' σε μορφή που ταιριάζει ένα προς ένα με τη σύνταξη του SVG. Εάν το δεδομένο χαρακτηριστικό ή ιδιότητα κινείται, περιέχει την τρέχουσα κινούμενη τιμή του χαρακτηριστικού ή της ιδιότητας και τόσο το ίδιο το αντικείμενο όσο και τα περιεχόμενά του διαβάζονται μόνο. Εάν το δεδομένο χαρακτηριστικό ή ιδιότητα δεν κινείται αυτήν τη στιγμή, περιέχει την ίδια τιμή με το pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Παρέχει πρόσβαση στα βασικά (δηλαδή, στατικά) περιεχόμενα του χαρακτηριστικού 'd' σε μορφή που ταιριάζει ένα προς ένα με τη σύνταξη του SVG. Έτσι, εάν το χαρακτηριστικό 'd' έχει μια εντολή "absolute moveto (M)" και "absolute arcto (A)", τότε το pathSegList θα έχει δύο καταχωρήσεις: μια SVG_PATHSEG_MOVETO_ABS και μια SVG_PATHSEG_ARC_ABS. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Svg.Paths](../../aspose.svg.paths/)
* συνέλευση [Aspose.SVG](../../)


