---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddPolyline. Προσθέτει μια διαμόρφωση στοιχείου polyline στον builder."
type: docs
weight: 430
url: /el/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

Προσθέτει μια διαμόρφωση στοιχείου 'polyline' στον κατασκευαστή.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'polyline'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

Προσθέτει ένα στοιχείο 'polyline' στον δημιουργό SVG, καθορίζοντας τις κορυφές του και τα στυλ.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'polyline'. |
| σημεία | Ένας πίνακας διπλών αριθμών που αντιπροσωπεύει τα σημεία του polyline (εναλλασσόμενες συντεταγμένες x και y). |
| fill | Το χρώμα γεμίσματος ή το στυλ βαφής για το polyline. Μπορεί να είναι μια τιμή Color ή Paint enum ή αναγνωριστικό διακομιστή βαφής. Προαιρετική παράμετρος. |
| stroke | Το χρώμα περιγράμματος ή το στυλ βαφής για το polyline. Μπορεί να είναι μια τιμή Color ή Paint enum ή αναγνωριστικό διακομιστή βαφής. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο polyline. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του builder του στοιχείου polyline. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
