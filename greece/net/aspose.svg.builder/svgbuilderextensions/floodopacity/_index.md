---
title: "SVGBuilderExtensions.FloodOpacity"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions FloodOpacity method. Ορίζει το χαρακτηριστικό flood-opacity για ένα στοιχείο SVG. Η τιμή πρέπει να είναι μεταξύ 0.0 πλήρως διαφανές και 1.0 πλήρως αδιαφανές"
type: docs
weight: 860
url: /el/net/aspose.svg.builder/svgbuilderextensions/floodopacity/
---
## SVGBuilderExtensions.FloodOpacity<TBuilder> method

Ορίζει το χαρακτηριστικό 'flood-opacity' για ένα στοιχείο SVG. Η τιμή πρέπει να είναι μεταξύ 0.0 (πλήρως διαφανές) και 1.0 (πλήρως αδιαφανές).

```csharp
public static TBuilder FloodOpacity<TBuilder>(this TBuilder builder, double opacity)
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
