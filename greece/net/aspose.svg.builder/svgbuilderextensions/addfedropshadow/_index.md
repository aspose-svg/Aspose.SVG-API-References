---
title: "SVGBuilderExtensions.AddFeDropShadow"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions AddFeDropShadow μέθοδος. Προσθέτει μια διαμόρφωση στοιχείου feDropShadow στον δημιουργό. Αυτό το στοιχείο δημιουργεί ένα εφέ σκιάς."
type: docs
weight: 200
url: /el/net/aspose.svg.builder/svgbuilderextensions/addfedropshadow/
---
## AddFeDropShadow<TBuilder>(*this TBuilder, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow}

Προσθέτει μια διαμόρφωση στοιχείου 'feDropShadow' στον δημιουργό. Αυτό το στοιχείο δημιουργεί ένα εφέ σκίασης.

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, 
    Action<SVGFEDropShadowElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'feDropShadow'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDropShadow<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow_1}

Προσθέτει ένα στοιχείο 'feDropShadow' στον δημιουργό SVG, δημιουργώντας ένα εφέ σκίασης για το εισερχόμενο γραφικό.

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<double, (double, double)> stdDeviation = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDropShadowElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Η παρουσία του δημιουργού SVG στην οποία θα προστεθεί το στοιχείο 'feDropShadow'. |
| dx | Η οριζόντια μετατόπιση για τη σκιά. Προαιρετική παράμετρος. |
| dy | Η κάθετη μετατόπιση για τη σκιά. Προαιρετική παράμετρος. |
| stdDeviation | Η τυπική απόκλιση για τη λειτουργία θόλωσης στη σκιά. Μπορεί να είναι διπλός αριθμός ή ValueTuple από δύο διπλούς αριθμούς. Προαιρετική παράμετρος. |
| in | Το εισαγόμενο γραφικό στο οποίο θα εφαρμοστεί η σκιά. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFEDropShadowElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
