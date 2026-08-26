---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions AddRect method. Προσθέτει μια διαμόρφωση στοιχείου rect στον builder."
type: docs
weight: 450
url: /el/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Προσθέτει μια διαμόρφωση στοιχείου 'rect' στον κατασκευαστή.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'rect'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

Προσθέτει ένα στοιχείο 'rect' (ορθογώνιο) με καθορισμένες διαστάσεις και στυλ στον κατασκευαστή SVG.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'rect'. |
| x | Η συντεταγμένη x του σημείου εκκίνησης του ορθογωνίου. Μπορεί να είναι μια τιμή double ή ένα πλέγμα (tuple) double και LengthType. |
| y | Η συντεταγμένη y του σημείου εκκίνησης του ορθογωνίου. Μπορεί να είναι μια τιμή double ή ένα πλέγμα (tuple) double και LengthType. |
| width | Το πλάτος του ορθογωνίου. Μπορεί να είναι μια τιμή double ή μια πλειάδα double και LengthType. |
| height | Το ύψος του ορθογωνίου. Μπορεί να είναι μια τιμή double ή μια πλειάδα double και LengthType. |
| fill | Το χρώμα γεμίσματος ή το στυλ βαφής για το ορθογώνιο. Μπορεί να είναι ένα Color ή μια τιμή enum Paint ή το paint server ID. Προαιρετική παράμετρος. |
| stroke | Το χρώμα περιγράμματος ή το στυλ βαφής για το περίγραμμα του ορθογωνίου. Μπορεί να είναι ένα Color ή μια τιμή enum Paint ή το paint server ID. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο ορθογωνίου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του δημιουργού στοιχείου ορθογωνίου. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
