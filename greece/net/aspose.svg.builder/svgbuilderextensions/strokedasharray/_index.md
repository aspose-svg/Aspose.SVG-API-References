---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος StrokeDashArray του SVGBuilderExtensions. Ορίζει το χαρακτηριστικό stroke-dasharray για ένα στοιχείο SVG, ορίζοντας το μοτίβο των παύλων και κενών που χρησιμοποιείται για τη βαφή της γραμμής."
type: docs
weight: 2090
url: /el/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

Ορίζει το χαρακτηριστικό 'stroke-dasharray' για ένα στοιχείο SVG, καθορίζοντας το μοτίβο των παύλων και κενών που χρησιμοποιούνται για τη βαφή του stroke.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| dashArray | Ο πίνακας των μηκών παύλων. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

Ορίζει το χαρακτηριστικό 'stroke-dasharray' για ένα στοιχείο SVG χρησιμοποιώντας προεπιλεγμένο μοτίβο παύλων.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| τιμή | Το μοτίβο παύλας προς ορισμό. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
