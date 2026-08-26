---
title: "SVGBuilderExtensions.AddFeComposite"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddFeComposite. Προσθέτει μια διαμόρφωση στοιχείου feComposite στον δημιουργό. Αυτό το στοιχείο εκτελεί μια δυαδική συνδυαστική λειτουργία δύο εισερχόμενων γραφικών"
type: docs
weight: 160
url: /el/net/aspose.svg.builder/svgbuilderextensions/addfecomposite/
---
## AddFeComposite<TBuilder>(*this TBuilder, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite}

Προσθέτει μια διαμόρφωση στοιχείου 'feComposite' στον δημιουργό. Αυτό το στοιχείο εκτελεί δυαδικό συνδυασμό δύο εισερχόμενων γραφικών.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    Action<SVGFECompositeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'feComposite'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComposite<TBuilder>(*this TBuilder, CompositeOperator?, double?, double?, double?, double?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite_1}

Προσθέτει ένα στοιχείο 'feComposite' στον δημιουργό SVG, καθορίζοντας τη λειτουργία σύνθεσης και διάφορες άλλες ιδιότητες για τον συνδυασμό των εισερχόμενων εικόνων.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    CompositeOperator? compositeOperator, double? k1, double? k2, double? k3, double? k4, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFECompositeElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Η παρουσία του δημιουργού SVG στην οποία θα προστεθεί το στοιχείο 'feComposite'. |
| compositeOperator | Ο τελεστής σύνθεσης που θα χρησιμοποιηθεί. Προαιρετική παράμετρος. |
| k1 | Η πρώτη αριθμητική τιμή για τη λειτουργία σύνθεσης. Προαιρετική παράμετρος. |
| k2 | Η δεύτερη αριθμητική τιμή για τη λειτουργία σύνθεσης. Προαιρετική παράμετρος. |
| k3 | Η τρίτη αριθμητική τιμή για τη λειτουργία σύνθεσης. Προαιρετική παράμετρος. |
| k4 | Η τέταρτη αριθμητική τιμή για τη λειτουργία σύνθεσης. Προαιρετική παράμετρος. |
| in | Η πρώτη είσοδος για το αποτέλεσμα σύνθεσης. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| in2 | Η δεύτερη είσοδος για το αποτέλεσμα σύνθεσης. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFECompositeElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* enum [CompositeOperator](../../compositeoperator/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
