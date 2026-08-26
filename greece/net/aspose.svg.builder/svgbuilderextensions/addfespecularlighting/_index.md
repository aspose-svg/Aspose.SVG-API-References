---
title: "SVGBuilderExtensions.AddFeSpecularLighting"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddFeSpecularLighting. Προσθέτει μια διαμόρφωση στοιχείου feSpecularLighting στον δημιουργό. Αυτό το στοιχείο εφαρμόζει ένα φωτιστικό εφέ στην εικόνα προσομοιώνοντας την καθρεπτική ανάκλαση."
type: docs
weight: 270
url: /el/net/aspose.svg.builder/svgbuilderextensions/addfespecularlighting/
---
## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_2}

Προσθέτει μια διαμόρφωση στοιχείου 'feSpecularLighting' στον δημιουργό. Αυτό το στοιχείο εφαρμόζει ένα εφέ φωτισμού στην εικόνα, προσομοιώνοντας την ειδική αντανάκλαση.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpecularLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'feSpecularLighting'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting}

Προσθέτει ένα στοιχείο 'feSpecularLighting' στον δημιουργό SVG, εφαρμόζοντας ένα ειδικό εφέ φωτισμού χρησιμοποιώντας μια καθορισμένη πηγή φωτός.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Η παρουσία του δημιουργού SVG στην οποία θα προστεθεί το στοιχείο 'feSpecularLighting'. |
| lightSource | Μια ενέργεια για τη διαμόρφωση της πηγής φωτός για το εφέ καθρεπτικού φωτισμού. |
| lightingColor | Το χρώμα του φωτός. Προαιρετική παράμετρος. |
| surfaceScale | Ο συντελεστής κλίμακας επιφάνειας για το εφέ φωτισμού. Προαιρετική παράμετρος. |
| specularConstant | Η σταθερά που χρησιμοποιείται για την κλίμακα του καθρεπτικού όρου. Προαιρετική παράμετρος. |
| specularExponent | Ο εκθέτης για τον καθρεπτικό όρο, ελέγχοντας την εστίαση της καθρεπτικής ανάγλυφης. Προαιρετική παράμετρος. |
| kernelUnitLength | Το μήκος μονάδας πυρήνα για το φίλτρο συνέλιξης. Μπορεί να είναι διπλό ή ένα ValueTuple από δύο διπλά. Προαιρετική παράμετρος. |
| in | Η εικόνα εισόδου στην οποία θα εφαρμοστεί το εφέ καθρεπτικού φωτισμού. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFESpecularLightingElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_1}

Προσθέτει ένα στοιχείο 'feSpecularLighting' στον δημιουργό SVG, εφαρμόζοντας ένα ειδικό εφέ φωτισμού χρησιμοποιώντας μια καθορισμένη πηγή φωτός.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Η παρουσία του δημιουργού SVG στην οποία θα προστεθεί το στοιχείο 'feSpecularLighting'. |
| lightSource | Μια ενέργεια για τη διαμόρφωση της πηγής φωτός για το εφέ καθρεπτικού φωτισμού. |
| lightingColor | Το χρώμα του φωτός. Προαιρετική παράμετρος. |
| surfaceScale | Ο συντελεστής κλίμακας επιφάνειας για το εφέ φωτισμού. Προαιρετική παράμετρος. |
| specularConstant | Η σταθερά που χρησιμοποιείται για την κλίμακα του καθρεπτικού όρου. Προαιρετική παράμετρος. |
| specularExponent | Ο εκθέτης για τον καθρεπτικό όρο, ελέγχοντας την εστίαση της καθρεπτικής ανάγλυφης. Προαιρετική παράμετρος. |
| kernelUnitLength | Το μήκος μονάδας πυρήνα για το φίλτρο συνέλιξης. Μπορεί να είναι διπλό ή ένα ValueTuple από δύο διπλά. Προαιρετική παράμετρος. |
| in | Η εικόνα εισόδου στην οποία θα εφαρμοστεί το εφέ καθρεπτικού φωτισμού. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFESpecularLightingElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_3}

Προσθέτει ένα στοιχείο 'feSpecularLighting' στον δημιουργό SVG, εφαρμόζοντας ένα ειδικό εφέ φωτισμού χρησιμοποιώντας μια καθορισμένη πηγή φωτός.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Η παρουσία του δημιουργού SVG στην οποία θα προστεθεί το στοιχείο 'feSpecularLighting'. |
| lightSource | Μια ενέργεια για τη διαμόρφωση της πηγής φωτός για το εφέ καθρεπτικού φωτισμού. |
| lightingColor | Το χρώμα του φωτός. Προαιρετική παράμετρος. |
| surfaceScale | Ο συντελεστής κλίμακας επιφάνειας για το εφέ φωτισμού. Προαιρετική παράμετρος. |
| specularConstant | Η σταθερά που χρησιμοποιείται για την κλίμακα του καθρεπτικού όρου. Προαιρετική παράμετρος. |
| specularExponent | Ο εκθέτης για τον καθρεπτικό όρο, ελέγχοντας την εστίαση της καθρεπτικής ανάγλυφης. Προαιρετική παράμετρος. |
| kernelUnitLength | Το μήκος μονάδας πυρήνα για το φίλτρο συνέλιξης. Μπορεί να είναι διπλό ή ένα ValueTuple από δύο διπλά. Προαιρετική παράμετρος. |
| in | Η εικόνα εισόδου στην οποία θα εφαρμοστεί το εφέ καθρεπτικού φωτισμού. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFESpecularLightingElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
