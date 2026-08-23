---
title: "SVGBuilderExtensions.AddFeFlood"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddFeFlood. تُضيف تكوين عنصر feFlood إلى المُنشئ. هذا العنصر يملأ منطقة الفلتر الفرعية بلون محدد."
type: docs
weight: 210
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addfeflood/
---
## AddFeFlood<TBuilder>(*this TBuilder, Action&lt;SVGFEFloodElementBuilder&gt;*) {#addfeflood}

يضيف تكوين عنصر 'feFlood' إلى المنشئ. هذا العنصر يملأ الجزء الفرعي للمرشح بلون محدد.

```csharp
public static TBuilder AddFeFlood<TBuilder>(this TBuilder builder, 
    Action<SVGFEFloodElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'feFlood'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGFEFloodElementBuilder](../../svgfefloodelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeFlood<TBuilder>(*this TBuilder, Color?, double?, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEFloodElementBuilder&gt;*) {#addfeflood_1}

يضيف عنصر 'feFlood' إلى منشئ SVG، مُنشئًا تأثير لون فيضان موحد على كامل الجزء الفرعي للمرشح.

```csharp
public static TBuilder AddFeFlood<TBuilder>(this TBuilder builder, Color? floodColor = default, 
    double? floodOpacity = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEFloodElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'feFlood'. |
| floodColor | اللون المستخدم لتأثير الفيض. معامل اختياري. |
| floodOpacity | مستوى الشفافية للون الفيض. معامل اختياري. |
| result | معرّف النتيجة لهذا العنصر الأساسي للمرشح. معلمة اختيارية. |
| x | الإحداثي السيني لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| y | الإحداثي الصادي لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| width | العرض لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| height | الارتفاع لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| fill | لون التعبئة أو الطلاء أو معرف خادم الطلاء للعنصر. معلمة اختيارية. |
| stroke | لون الحد أو الطلاء أو معرف خادم الطلاء للعنصر. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر الفلتر الأولي. معلمة اختيارية. |
| extend | إجراء اختياري لتكوين إضافي لـ SVGFEFloodElementBuilder. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEFloodElementBuilder](../../svgfefloodelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
