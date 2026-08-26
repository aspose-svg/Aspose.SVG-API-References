---
title: "SVGBuilderExtensions.AddFeDiffuseLighting"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος AddFeDiffuseLighting του SVGBuilderExtensions. Προσθέτει μια διαμόρφωση του στοιχείου feDiffuseLighting στον κατασκευαστή. Αυτό το στοιχείο παρέχει εφέ φωτισμού σε μια εικόνα."
type: docs
weight: 180
url: /el/net/aspose.svg.builder/svgbuilderextensions/addfediffuselighting/
---
## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting}

Προσθέτει μια διαμόρφωση στοιχείου 'feDiffuseLighting' στον δημιουργό. Αυτό το στοιχείο παρέχει ένα εφέ φωτισμού σε μια εικόνα.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDiffuseLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'feDiffuseLighting'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_1}

Προσθέτει ένα στοιχείο 'feDiffuseLighting' στον δημιουργό SVG, εφαρμόζοντας ένα διάχυτο εφέ φωτισμού χρησιμοποιώντας μια καθορισμένη πηγή φωτός.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'feDiffuseLighting'. |
| lightSource | Μια ενέργεια για τη διαμόρφωση της πηγής φωτός για το εφέ διαχυτικού φωτισμού. |
| lightingColor | Το χρώμα του φωτός. Προαιρετική παράμετρος. |
| surfaceScale | Ο συντελεστής κλίμακας επιφάνειας για το εφέ φωτισμού. Προαιρετική παράμετρος. |
| diffuseConstant | Η σταθερά που χρησιμοποιείται για τον καθορισμό του εφέ φωτισμού. Προαιρετική παράμετρος. |
| in | Η είσοδος για το εφέ διαχυτικού φωτισμού. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFEDiffuseLightingElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_2}

Προσθέτει ένα στοιχείο 'feDiffuseLighting' στον δημιουργό SVG, εφαρμόζοντας ένα διάχυτο εφέ φωτισμού χρησιμοποιώντας μια καθορισμένη πηγή φωτός.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'feDiffuseLighting'. |
| lightSource | Μια ενέργεια για τη διαμόρφωση της πηγής φωτός για το εφέ διαχυτικού φωτισμού. |
| lightingColor | Το χρώμα του φωτός. Προαιρετική παράμετρος. |
| surfaceScale | Ο συντελεστής κλίμακας επιφάνειας για το εφέ φωτισμού. Προαιρετική παράμετρος. |
| diffuseConstant | Η σταθερά που χρησιμοποιείται για τον καθορισμό του εφέ φωτισμού. Προαιρετική παράμετρος. |
| in | Η είσοδος για το εφέ διαχυτικού φωτισμού. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFEDiffuseLightingElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_3}

Προσθέτει ένα στοιχείο 'feDiffuseLighting' στον δημιουργό SVG, εφαρμόζοντας ένα διάχυτο εφέ φωτισμού χρησιμοποιώντας μια καθορισμένη πηγή φωτός.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'feDiffuseLighting'. |
| lightSource | Μια ενέργεια για τη διαμόρφωση της πηγής φωτός για το εφέ διαχυτικού φωτισμού. |
| lightingColor | Το χρώμα του φωτός. Προαιρετική παράμετρος. |
| surfaceScale | Ο συντελεστής κλίμακας επιφάνειας για το εφέ φωτισμού. Προαιρετική παράμετρος. |
| diffuseConstant | Η σταθερά που χρησιμοποιείται για τον καθορισμό του εφέ φωτισμού. Προαιρετική παράμετρος. |
| in | Η είσοδος για το εφέ διαχυτικού φωτισμού. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFEDiffuseLightingElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
