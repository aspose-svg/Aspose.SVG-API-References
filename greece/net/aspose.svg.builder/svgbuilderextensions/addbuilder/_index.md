---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddBuilder. Προσθέτει έναν υπάρχοντα δημιουργό στοιχείου SVG στον τρέχοντα δημιουργό στοιχείου SVG. Αυτή η μέθοδος χρησιμοποιείται για την ένταξη ενός προεπιλεγμένου δημιουργού στοιχείου SVG στον τρέχοντα δημιουργό."
type: docs
weight: 60
url: /el/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Προσθέτει έναν υπάρχοντα δημιουργό στοιχείου SVG στον τρέχοντα δημιουργό στοιχείου SVG. Αυτή η μέθοδος χρησιμοποιείται για την ένταξη ενός προκαθορισμένου δημιουργού στοιχείου SVG στον τρέχοντα δημιουργό.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| TElementBuilder | Ο τύπος του δημιουργού στοιχείου SVG που θα διαμορφωθεί. Το TElementBuilder πρέπει να υλοποιεί το ISVGElementBuilder. |
| builder | Ο δημιουργός στοιχείου SVG στον οποίο προστίθεται ο άλλος δημιουργός στοιχείου. |
| elementBuilder | Ο κατασκευαστής στοιχείου SVG που θα προστεθεί. |

### Τιμή Επιστροφής

Ο αρχικός δημιουργός στοιχείου SVG για αλυσίδωση μεθόδων.

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
