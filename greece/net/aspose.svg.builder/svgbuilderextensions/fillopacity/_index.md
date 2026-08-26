---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions FillOpacity. Ορίζει την ιδιότητα fill-opacity για ένα στοιχείο SVG. Η τιμή πρέπει να είναι μεταξύ 0.0 πλήρως διαφανούς και 1.0 πλήρως αδιαφανούς"
type: docs
weight: 820
url: /el/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Ορίζει το χαρακτηριστικό 'fill-opacity' για ένα στοιχείο SVG. Η τιμή πρέπει να είναι μεταξύ 0.0 (πλήρως διαφανής) και 1.0 (πλήρως αδιαφανής).

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| opacity | Η τιμή διαφάνειας που θα οριστεί. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentOutOfRangeException | Εκτοπίζεται εάν η διαφάνεια δεν είναι εντός του έγκυρου εύρους. |

### Δείτε επίσης

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
