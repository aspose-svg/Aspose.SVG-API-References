---
title: "SVGBuilderExtensions.AddPattern"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος AddPattern του SVGBuilderExtensions. Προσθέτει μια διαμόρφωση στοιχείου pattern στον builder"
type: docs
weight: 410
url: /el/net/aspose.svg.builder/svgbuilderextensions/addpattern/
---
## AddPattern<TBuilder>(*this TBuilder, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern}

Προσθέτει μια διαμόρφωση στοιχείου 'pattern' στον κατασκευαστή.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, 
    Action<SVGPatternElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'pattern'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPattern<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, string, string, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern_1}

Προσθέτει ένα στοιχείο 'pattern' στον δημιουργό SVG, καθορίζοντας το σύστημα συντεταγμένων και τις μονάδες για το περιεχόμενο του μοτίβου.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, CoordinateUnits? patternUnits, 
    CoordinateUnits? patternContentUnits, string href = null, string id = null, 
    Action<SVGPatternElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'pattern'. |
| patternUnits | Καθορίζει το σύστημα συντεταγμένων για το pattern. Προαιρετική παράμετρος. |
| patternContentUnits | Καθορίζει το σύστημα συντεταγμένων για το περιεχόμενο εντός του pattern. Προαιρετική παράμετρος. |
| href | Η αναφορά σε άλλο pattern, εάν υπάρχει. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο pattern. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του builder του στοιχείου pattern. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* enum [CoordinateUnits](../../coordinateunits/)
* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
