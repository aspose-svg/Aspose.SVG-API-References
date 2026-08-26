---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddRadialGradient. Προσθέτει μια διαμόρφωση στοιχείου radialGradient στον κατασκευαστή"
type: docs
weight: 440
url: /el/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Προσθέτει μια διαμόρφωση στοιχείου 'radialGradient' στον κατασκευαστή.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'radialGradient'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Προσθέτει ένα στοιχείο 'radialGradient' στον δημιουργό SVG, καθορίζοντας το κέντρο, την ακτίνα και τα εστιακά σημεία, μαζί με άλλες ιδιότητες διαβάθμισης.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του κατασκευαστή SVG στο οποίο θα προστεθεί το στοιχείο 'radialGradient'. |
| cx | Η συντεταγμένη x του κέντρου της διαβάθμισης. Μπορεί να είναι τύπου double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| cy | Η συντεταγμένη y του κέντρου της διαβάθμισης. Μπορεί να είναι τύπου double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| r | Η ακτίνα της διαβάθμισης. Μπορεί να είναι τύπου double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fx | Η συντεταγμένη x του σημείου εστίασης της διαβάθμισης. Μπορεί να είναι τύπου double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fy | Η συντεταγμένη y του εστιακού σημείου της διαβάθμισης. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| gradientUnits | Καθορίζει το σύστημα συντεταγμένων για τη διαβάθμιση. Προαιρετική παράμετρος. |
| spreadMethod | Ορίζει πώς η διαβάθμιση εξαπλώνεται πέρα από τα σημεία έναρξης και λήξης της. Προαιρετική παράμετρος. |
| href | Η αναφορά σε άλλη διαβάθμιση, εφόσον υπάρχει. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο διαβάθμισης. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του δημιουργού στοιχείου κυκλικής διαβάθμισης. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
