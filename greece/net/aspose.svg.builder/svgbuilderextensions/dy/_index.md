---
title: "SVGBuilderExtensions.Dy"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions Dy. Ορίζει πολλαπλές τιμές κάθετης προσαρμογής για το περιεχόμενο κειμένου."
type: docs
weight: 780
url: /el/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

Ορίζει πολλαπλές κάθετες τιμές προσαρμογής για το κείμενο.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμές | Ο πίνακας των τιμών κάθετης προσαρμογής. |
| type | Ο τύπος μονάδας μήκους για τις τιμές. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Αυτή η μέθοδος ορίζει το χαρακτηριστικό 'dy' με πολλαπλές τιμές, επιτρέποντας ατομικές κάθετες προσαρμογές για κάθε χαρακτήρα ή τμήμα κειμένου.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

Ορίζει μια μοναδική κάθετη τιμή προσαρμογής για το κείμενο.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η τιμή κάθετης προσαρμογής. |
| type | Ο τύπος μονάδας μήκους για την τιμή. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Αυτή η μέθοδος ορίζει το χαρακτηριστικό 'dy' με μία τιμή, ρυθμίζοντας τη κάθετη θέση του περιεχομένου κειμένου.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
