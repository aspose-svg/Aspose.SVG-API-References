---
title: "SVGBuilderExtensions.From"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions From. Ορίζει το χαρακτηριστικό from που καθορίζει την αρχική τιμή της κίνησης με συγκεκριμένο τύπο μήκους"
type: docs
weight: 960
url: /el/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

Ορίζει το χαρακτηριστικό 'from', ορίζοντας την αρχική τιμή της κίνησης με έναν καθορισμένο τύπο μήκους.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η αρχική τιμή για την κίνηση. |
| type | Ο τύπος μήκους για την τιμή 'from'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
