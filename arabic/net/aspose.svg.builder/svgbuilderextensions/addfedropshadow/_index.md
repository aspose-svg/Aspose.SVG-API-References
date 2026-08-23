---
title: "SVGBuilderExtensions.AddFeDropShadow"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddFeDropShadow. إضافة تكوين عنصر feDropShadow إلى المُنشئ. هذا العنصر يُنشئ تأثير الظل المنسدل"
type: docs
weight: 200
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addfedropshadow/
---
## AddFeDropShadow<TBuilder>(*this TBuilder, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow}

يضيف تكوين عنصر 'feDropShadow' إلى المنشئ. هذا العنصر ينشئ تأثير ظل إسقاط.

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, 
    Action<SVGFEDropShadowElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'feDropShadow'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDropShadow<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow_1}

يضيف عنصر 'feDropShadow' إلى منشئ SVG، مُنشئًا تأثير ظل إسقاط للرسمة المدخلة.

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

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'feDropShadow'. |
| dx | الإزاحة الأفقية للظل المنسدل. معلمة اختيارية. |
| dy | الإزاحة العمودية للظل المنسدل. معلمة اختيارية. |
| stdDeviation | الانحراف المعياري لعملية الضبابية في الظل المنسدل. يمكن أن يكون عددًا مزدوجًا أو ValueTuple من عددين مزدوجين. معلمة اختيارية. |
| in | الرسمة الإدخالية التي سيُطبق عليها الظل المنسدل. يمكن أن تكون سلسلة نصية أو FilterInput. معلمة اختيارية. |
| result | معرّف النتيجة لهذا العنصر الأساسي للمرشح. معلمة اختيارية. |
| x | الإحداثي السيني لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| y | الإحداثي الصادي لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| width | العرض لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| height | الارتفاع لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| fill | لون التعبئة أو الطلاء أو معرف خادم الطلاء للعنصر. معلمة اختيارية. |
| stroke | لون الحد أو الطلاء أو معرف خادم الطلاء للعنصر. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر الفلتر الأولي. معلمة اختيارية. |
| extend | إجراء اختياري لمزيد من تكوين SVGFEDropShadowElementBuilder. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

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
