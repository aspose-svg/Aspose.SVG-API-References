---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions Rect method. Ορίζει τα χαρακτηριστικά x y width και height για ένα στοιχείο SVG ώστε να ορίσει ένα ορθογώνιο."
type: docs
weight: 1920
url: /el/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Ορίζει τα χαρακτηριστικά 'x', 'y', 'width' και 'height' για ένα στοιχείο SVG ώστε να ορίσει ένα ορθογώνιο.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| x | Η συντεταγμένη x του ορθογωνίου. |
| y | Η συντεταγμένη y του ορθογωνίου. |
| width | Το πλάτος του ορθογωνίου. |
| height | Το ύψος του ορθογωνίου. |
| type | Ο τύπος μέτρησης μήκους για όλες τις διαστάσεις (η προεπιλογή είναι εικονοστοιχεία). |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
