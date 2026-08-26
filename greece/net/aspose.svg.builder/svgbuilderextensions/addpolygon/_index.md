---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Η μέθοδος SVGBuilderExtensions AddPolygon. Προσθέτει μια διαμόρφωση στοιχείου πολυγώνου στον builder"
type: docs
weight: 420
url: /el/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Προσθέτει μια διαμόρφωση στοιχείου 'polygon' στον κατασκευαστή.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'polygon'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

Προσθέτει ένα στοιχείο 'polygon' στον δημιουργό SVG, καθορίζοντας τις κορυφές του και τα στυλ.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Η παρουσία του SVG builder στην οποία θα προστεθεί το στοιχείο 'polygon'. |
| σημεία | Ένας πίνακας δεκαδικών αριθμών που αντιπροσωπεύει τα σημεία του πολυγώνου (εναλλασσόμενες συντεταγμένες x και y). |
| fill | Το χρώμα γεμίσματος ή το στυλ βαφής για το πολύγωνο. Μπορεί να είναι μια τιμή Color ή Paint enum ή αναγνωριστικό διακομιστή βαφής. Προαιρετική παράμετρος. |
| stroke | Το χρώμα περιγράμματος ή το στυλ βαφής για το πολύγωνο. Μπορεί να είναι μια τιμή Color ή Paint enum ή αναγνωριστικό διακομιστή βαφής. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο πολυγώνου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του κατασκευαστή στοιχείου πολυγώνου. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
