---
title: "SVGBuilderExtensions.AddFeColorMatrix"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddFeColorMatrix. Προσθέτει μια διαμόρφωση στοιχείου feColorMatrix στον builder. Αυτό το στοιχείο εφαρμόζει μια μετασχηματιστική μήτρα στις τιμές χρώματος και άλφα κάθε εικονοστοιχείου."
type: docs
weight: 140
url: /el/net/aspose.svg.builder/svgbuilderextensions/addfecolormatrix/
---
## AddFeColorMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEColorMatrixElementBuilder&gt;*) {#addfecolormatrix_1}

Προσθέτει μια διαμόρφωση στοιχείου 'feColorMatrix' στον δημιουργό. Αυτό το στοιχείο εφαρμόζει μια μετασχηματιστική μήτρα στα χρώματα και τις τιμές άλφα κάθε εικονοστοιχείου.

```csharp
public static TBuilder AddFeColorMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEColorMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'feColorMatrix'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGFEColorMatrixElementBuilder](../../svgfecolormatrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeColorMatrix<TBuilder>(*this TBuilder, [ColorMatrixOperation](../../colormatrixoperation/), double[], OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEColorMatrixElementBuilder&gt;*) {#addfecolormatrix}

Προσθέτει ένα στοιχείο 'feColorMatrix' στον δημιουργό SVG, καθορίζοντας τον τύπο λειτουργίας της χρωματικής μήτρας και διάφορες άλλες ιδιότητες για το εφέ φίλτρου.

```csharp
public static TBuilder AddFeColorMatrix<TBuilder>(this TBuilder builder, ColorMatrixOperation type, 
    double[] values = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEColorMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'feColorMatrix'. |
| type | Τύπος λειτουργίας μήτρας χρώματος που θα εφαρμοστεί. |
| τιμές | Οι τιμές για τη λειτουργία μήτρας χρώματος. Προαιρετική παράμετρος. |
| in | Η είσοδος για το εφέ μήτρας χρώματος. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFEColorMatrixElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEColorMatrixElementBuilder](../../svgfecolormatrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
