---
title: "SVGBuilderExtensions.AddFeDisplacementMap"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος AddFeDisplacementMap του SVGBuilderExtensions. Προσθέτει μια διαμόρφωση στοιχείου feDisplacementMap στον builder. Αυτό το στοιχείο μετατοπίζει μια εικόνα με βάση έναν καθορισμένο χάρτη διανυσμάτων."
type: docs
weight: 190
url: /el/net/aspose.svg.builder/svgbuilderextensions/addfedisplacementmap/
---
## AddFeDisplacementMap<TBuilder>(*this TBuilder, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap}

Προσθέτει μια διαμόρφωση στοιχείου 'feDisplacementMap' στον δημιουργό. Αυτό το στοιχείο μετατοπίζει μια εικόνα με έναν καθορισμένο διανυσματικό χάρτη.

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, 
    Action<SVGFEDisplacementMapElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'feDisplacementMap'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDisplacementMap<TBuilder>(*this TBuilder, double?, ChannelSelector?, ChannelSelector?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap_1}

Προσθέτει ένα στοιχείο 'feDisplacementMap' στον δημιουργό SVG, δημιουργώντας ένα εφέ που παραμορφώνει μια εικόνα βάσει των δεδομένων χρώματος από μια δεύτερη πηγή.

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, double? scale = null, 
    ChannelSelector? xChannelSelector = default, ChannelSelector? yChannelSelector = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDisplacementMapElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του δημιουργού στοιχείων SVG, διευκολύνοντας τη ρευστή χρήση του API. |
| builder | Το στιγμιότυπο του SVG builder στο οποίο θα προστεθεί το στοιχείο 'feDisplacementMap'. |
| scale | Ο συντελεστής κλίμακας που καθορίζει το μέγεθος της μετατόπισης. Προαιρετική παράμετρος. |
| xChannelSelector | Το κανάλι της εικόνας in2 που θα χρησιμοποιηθεί για μετατόπιση κατά τον άξονα x. Προαιρετική παράμετρος. |
| yChannelSelector | Το κανάλι της εικόνας in2 που θα χρησιμοποιηθεί για μετατόπιση κατά τον άξονα y. Προαιρετική παράμετρος. |
| in | Η εικόνα εισόδου που θα μετατοπιστεί. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| in2 | Η εικόνα που παρέχει τα δεδομένα μετατόπισης. Μπορεί να είναι συμβολοσειρά ή FilterInput. Προαιρετική παράμετρος. |
| result | Το αναγνωριστικό αποτελέσματος για αυτό το φίλτρο primitive. Προαιρετική παράμετρος. |
| x | Η συντεταγμένη x της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| y | Η συντεταγμένη y της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| width | Το πλάτος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| height | Το ύψος της υποπεριοχής του primitive φίλτρου. Μπορεί να είναι double ή ValueTuple με LengthType. Προαιρετική παράμετρος. |
| fill | Το χρώμα γεμίσματος, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| stroke | Το χρώμα γραμμής, η βαφή ή το αναγνωριστικό του διακομιστή βαφής για το στοιχείο. Προαιρετική παράμετρος. |
| id | Το μοναδικό αναγνωριστικό για το στοιχείο primitive φίλτρου. Προαιρετική παράμετρος. |
| extend | Μια προαιρετική ενέργεια για περαιτέρω διαμόρφωση του SVGFEDisplacementMapElementBuilder. |

### Τιμή Επιστροφής

Το στιγμιότυπο του builder, επιτρέποντας αλυσιδωτή κλήση μεθόδων.

### Δείτε επίσης

* enum [ChannelSelector](../../channelselector/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
