---
title: "SVGBuilderExtensions.AddLine"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions AddLine method. Προσθέτει μια διαμόρφωση στοιχείου line στον builder"
type: docs
weight: 350
url: /el/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

Προσθέτει μια διαμόρφωση στοιχείου 'line' στον κατασκευαστή.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'line'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

Προσθέτει ένα στοιχείο 'line' με καθορισμένα σημεία έναρξης και λήξης, και στυλ, στον δημιουργό SVG.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Η παρουσία του SVG builder στην οποία θα προστεθεί το στοιχείο 'line'. |
| x1 | Η συντεταγμένη x του σημείου εκκίνησης της γραμμής. Μπορεί να είναι τιμή double ή πλειάδα (tuple) double και LengthType. |
| y1 | Η συντεταγμένη y του σημείου εκκίνησης της γραμμής. Μπορεί να είναι τιμή double ή πλειάδα (tuple) double και LengthType. |
| x2 | Η συντεταγμένη x του τελικού σημείου της γραμμής. Μπορεί να είναι τιμή double ή πλειάδα (tuple) double και LengthType. |
| y2 | Η συντεταγμένη y του τελικού σημείου της γραμμής. Μπορεί να είναι τιμή double ή πλειάδα (tuple) double και LengthType. |
| fill | Το χρώμα γεμίσματος ή το στυλ βαφής για τη γραμμή. Μπορεί να είναι Color ή τιμή enum Paint ή ID διακομιστή βαφής. Προαιρετική παράμετρος. |
| stroke | Το χρώμα περιγράμματος ή το στυλ βαφής για τη γραμμή. Μπορεί να είναι Color ή τιμή enum Paint ή ID διακομιστή βαφής. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο γραμμής. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του builder του στοιχείου γραμμής. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
