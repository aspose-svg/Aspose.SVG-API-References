---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions AddCircle μέθοδος. Προσθέτει μια διαμόρφωση στοιχείου κύκλου στον builder."
type: docs
weight: 70
url: /el/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

Προσθέτει μια διαμόρφωση στοιχείου 'circle' στον δημιουργό.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'circle'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

Προσθέτει ένα στοιχείο 'circle' με καθορισμένο κέντρο, ακτίνα και στυλ στον δημιουργό SVG.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Η παρουσία του SVG builder στην οποία θα προστεθεί το στοιχείο 'circle'. |
| cx | Η συντεταγμένη x του κέντρου του κύκλου. Μπορεί να είναι τιμή double ή πλειάδα double και LengthType. |
| cy | Η συντεταγμένη y του κέντρου του κύκλου. Μπορεί να είναι τιμή double ή πλειάδα double και LengthType. |
| r | Η ακτίνα του κύκλου. Μπορεί να είναι τιμή double ή πλειάδα double και LengthType. |
| fill | Το χρώμα γεμίσματος ή το στυλ βαφής για τον κύκλο. Μπορεί να είναι Color ή τιμή enum Paint ή ID διακομιστή βαφής. Προαιρετική παράμετρος. |
| stroke | Το χρώμα περιγράμματος ή το στυλ βαφής για το περίγραμμα του κύκλου. Μπορεί να είναι Color ή τιμή enum Paint ή ID διακομιστή βαφής. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο κύκλου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του builder του στοιχείου κύκλου. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
