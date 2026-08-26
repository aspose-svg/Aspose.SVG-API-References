---
title: "SVGBuilderExtensions.Dx"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions Dx. Ορίζει το χαρακτηριστικό dx για να ρυθμίσει τη οριζόντια θέση κάθε χαρακτήρα στο κείμενο."
type: docs
weight: 770
url: /el/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

Ορίζει το χαρακτηριστικό 'dx' για να προσαρμόσει τη οριζόντια θέση κάθε χαρακτήρα στο κείμενο.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| type | Ο τύπος μονάδας μήκους για τις τιμές. |
| τιμές | Οι τιμές οριζόντιας προσαρμογής για κάθε χαρακτήρα. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Αυτή η μέθοδος επιτρέπει ακριβή έλεγχο της οριζόντιας απόστασης των χαρακτήρων στο κείμενο.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Ορίζει μια μοναδική οριζόντια τιμή προσαρμογής για το κείμενο.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η τιμή οριζόντιας προσαρμογής. |
| type | Ο τύπος μονάδας μήκους για την τιμή. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Αυτή η μέθοδος ορίζει το χαρακτηριστικό 'dx' με μια μόνο τιμή, ρυθμίζοντας τη οριζόντια θέση του περιεχομένου κειμένου.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
