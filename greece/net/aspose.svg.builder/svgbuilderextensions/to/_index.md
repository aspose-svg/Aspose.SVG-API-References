---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions To μέθοδος. Ορίζει το χαρακτηριστικό to που καθορίζει την τελική τιμή της κίνησης με συγκεκριμένο τύπο μήκους"
type: docs
weight: 2250
url: /el/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Ορίζει το χαρακτηριστικό 'to', ορίζοντας την τελική τιμή της κινούμενης εικόνας με έναν καθορισμένο τύπο μήκους.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η τελική τιμή για την κίνηση. |
| type | Ο τύπος μήκους για την τιμή 'to'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
