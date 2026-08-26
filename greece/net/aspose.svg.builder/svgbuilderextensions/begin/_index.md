---
title: "SVGBuilderExtensions.Begin"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions Begin. Ορίζει το χαρακτηριστικό begin που καθορίζει πότε πρέπει να ξεκινήσει η animation"
type: docs
weight: 610
url: /el/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

Ορίζει το χαρακτηριστικό 'begin', καθορίζοντας πότε πρέπει να ξεκινήσει η animation.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| ρυθμίστε | Ένας delegate για τη διαμόρφωση της τιμής χρονισμού. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
