---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddLinearGradient. Προσθέτει μια διαμόρφωση στοιχείου linearGradient στον κατασκευαστή."
type: docs
weight: 360
url: /el/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Προσθέτει μια διαμόρφωση στοιχείου 'linearGradient' στον κατασκευαστή.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'linearGradient'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Προσθέτει ένα στοιχείο 'linearGradient' στον δημιουργό SVG, καθορίζοντας τις θέσεις έναρξης και λήξης του, μαζί με άλλες ιδιότητες διαβάθμισης.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το αντίγραφο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'linearGradient'. |
| x1 | Η αρχική συντεταγμένη x για το gradient. Μπορεί να είναι double ή ValueTuple με LengthType. |
| y1 | Η αρχική συντεταγμένη y για το gradient. Μπορεί να είναι double ή ValueTuple με LengthType. |
| x2 | Η τελική συντεταγμένη x για το gradient. Μπορεί να είναι double ή ValueTuple με LengthType. |
| y2 | Η τελική συντεταγμένη y για το gradient. Μπορεί να είναι double ή ValueTuple με LengthType. |
| gradientUnits | Καθορίζει το σύστημα συντεταγμένων για τη διαβάθμιση. Προαιρετική παράμετρος. |
| spreadMethod | Ορίζει πώς η διαβάθμιση εξαπλώνεται πέρα από τα σημεία έναρξης και λήξης της. Προαιρετική παράμετρος. |
| href | Η αναφορά σε άλλη διαβάθμιση, εφόσον υπάρχει. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο διαβάθμισης. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του linear gradient element builder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
