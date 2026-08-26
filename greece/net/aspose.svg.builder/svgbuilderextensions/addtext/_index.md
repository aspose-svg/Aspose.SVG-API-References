---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddText. Προσθέτει μια διαμόρφωση στοιχείου κειμένου στον κατασκευαστή."
type: docs
weight: 530
url: /el/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Προσθέτει μια διαμόρφωση στοιχείου 'text' στον κατασκευαστή.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'text'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Προσθέτει ένα στοιχείο 'text' με καθορισμένο περιεχόμενο και ιδιότητες στον κατασκευαστή SVG.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του κατασκευαστή στοιχείου SVG, που επιτρέπει την αλυσίδωση. |
| builder | Η παρουσία του κατασκευαστή στην οποία θα προστεθεί το στοιχείο 'text'. |
| content | Το περιεχόμενο κειμένου που θα εμφανιστεί μέσα στο στοιχείο 'text'. |
| x | Η συντεταγμένη x για το στοιχείο κειμένου. Μπορεί να είναι μια τιμή double ή ένα πλέγμα (tuple) από double και LengthType. |
| y | Η συντεταγμένη y για το στοιχείο κειμένου. Μπορεί να είναι μια τιμή double ή ένα πλέγμα (tuple) από double και LengthType. |
| fontSize | Το μέγεθος γραμματοσειράς για το κείμενο. Μπορεί να είναι μια τιμή double ή ένα πλέγμα (tuple) από double και LengthType. |
| fontStyle | Το στυλ γραμματοσειράς για το κείμενο (π.χ., normal, italic, oblique). |
| fontFamily | Η οικογένεια γραμματοσειρών για το κείμενο (π.χ., Arial, Verdana). |
| fontWeight | Το βάρος (πάχος) της γραμματοσειράς (π.χ., normal, bold). |
| fill | Το χρώμα γεμίσματος ή το στυλ βαφής για το κείμενο. Μπορεί να είναι μια τιμή Color ή Paint enum ή αναγνωριστικό διακομιστή βαφής. |
| stroke | Το χρώμα περιγράμματος ή το στυλ βαφής για το κείμενο. Μπορεί να είναι μια τιμή Color ή Paint enum ή αναγνωριστικό διακομιστή βαφής. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο κειμένου. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του δημιουργού στοιχείου κειμένου. |

### Τιμή Επιστροφής

Το αντικείμενο δημιουργού για αλυσίδωση περαιτέρω προσθηκών ή ρυθμίσεων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
