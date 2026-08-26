---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions By μέθοδος. Ορίζει το χαρακτηριστικό by που καθορίζει τη σχετική τιμή μετατόπισης για την κίνηση με έναν καθορισμένο τύπο μήκους."
type: docs
weight: 620
url: /el/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

Ορίζει το χαρακτηριστικό 'by', καθορίζοντας τη σχετική τιμή μετατόπισης για την animation με έναν καθορισμένο τύπο μήκους.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η σχετική τιμή μετατόπισης για την κίνηση. |
| type | Ο τύπος μήκους για την τιμή 'by'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
