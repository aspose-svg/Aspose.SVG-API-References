---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions Rotate μέθοδος. Ορίζει γωνίες περιστροφής για μεμονωμένους χαρακτήρες ή τμήματα του κειμένου"
type: docs
weight: 2000
url: /el/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Ορίζει γωνίες περιστροφής για μεμονωμένους χαρακτήρες ή τμήματα του κειμένου.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμές | Ένας πίνακας γωνιών περιστροφής σε μοίρες. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Αυτή η μέθοδος ορίζει το χαρακτηριστικό 'rotate' με πολλαπλές τιμές, επιτρέποντας την ατομική περιστροφή κάθε χαρακτήρα ή τμήματος κειμένου.

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Ορίζει μία μοναδική γωνία περιστροφής για ολόκληρο το κείμενο.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η γωνία περιστροφής σε μοίρες. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Αυτή η μέθοδος ορίζει το χαρακτηριστικό 'rotate' με μία τιμή, εφαρμόζοντας την ίδια γωνία περιστροφής σε όλο το κείμενο.

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
