---
title: "SVGBuilderExtensions.Y"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Η μέθοδος SVGBuilderExtensions Y. Ορίζει το χαρακτηριστικό y για ένα στοιχείο SVG"
type: docs
weight: 2400
url: /el/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

Ορίζει το χαρακτηριστικό 'y' για ένα στοιχείο SVG.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| τιμή | Η τιμή για το χαρακτηριστικό 'y'. |
| type | Ο τύπος μέτρησης μήκους (η προεπιλογή είναι εικονοστοιχεία). |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

Ορίζει το χαρακτηριστικό 'y' για την τοποθέτηση του κειμένου κατά μήκος του άξονα y.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| type | Ο τύπος μονάδας μήκους για τις τιμές. |
| τιμές | Οι τιμές θέσης του άξονα y. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Αυτή η μέθοδος ορίζει το χαρακτηριστικό 'y', το οποίο καθορίζει τις κάθετες θέσεις του στοιχείου κειμένου.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
