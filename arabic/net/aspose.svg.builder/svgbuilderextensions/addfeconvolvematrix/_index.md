---
title: "SVGBuilderExtensions.AddFeConvolveMatrix"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddFeConvolveMatrix. تضيف تكوين عنصر feConvolveMatrix إلى المُنشئ. هذا العنصر يطبق تأثير مرشح التلافيف المصفوفي."
type: docs
weight: 170
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addfeconvolvematrix/
---
## AddFeConvolveMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix_1}

يضيف تكوين عنصر 'feConvolveMatrix' إلى المنشئ. هذا العنصر يطبق تأثير مرشح الالتفاف المصفوفي.

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEConvolveMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'feConvolveMatrix'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeConvolveMatrix<TBuilder>(*this TBuilder, double[], double?, double?, int?, int?, EdgeMode?, bool?, OneOf&lt;int, (int, int)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix}

يضيف عنصر 'feConvolveMatrix' إلى منشئ SVG، مطبقًا تأثير مرشح الالتفاف المصفوفي.

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    double[] kernelMatrix = null, double? divisor = null, double? bias = null, int? targetX = null, 
    int? targetY = null, EdgeMode? edgeMode = default, bool? preserveAlpha = null, 
    OneOf<int, (int, int)> order = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEConvolveMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'feConvolveMatrix'. |
| kernelMatrix | مصفوفة القيم للتلافيف. معامل اختياري. |
| divisor | المقسِّم لعملية الالتفاف. معلمة اختيارية. |
| bias | التحيز الذي سيُضاف إلى نتيجة الالتفاف. معلمة اختيارية. |
| targetX | الإحداثي X للبكسل الهدف في مصفوفة النواة. معلمة اختيارية. |
| targetY | الإحداثي Y للبكسل الهدف في مصفوفة النواة. معلمة اختيارية. |
| edgeMode | يحدد كيفية معالجة بكسلات الحافة في الالتفاف. معلمة اختيارية. |
| preserveAlpha | يشير إلى ما إذا كان يجب الحفاظ على قناة ألفا. معلمة اختيارية. |
| order | ترتيب مصفوفة النواة. يمكن أن يكون عددًا صحيحًا أو ValueTuple من عددين صحيحين. معلمة اختيارية. |
| in | المدخل لتأثير الالتفاف. يمكن أن يكون سلسلة نصية أو FilterInput. معلمة اختيارية. |
| result | معرّف النتيجة لهذا العنصر الأساسي للمرشح. معلمة اختيارية. |
| x | الإحداثي السيني لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| y | الإحداثي الصادي لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| width | العرض لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| height | الارتفاع لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| fill | لون التعبئة أو الطلاء أو معرف خادم الطلاء للعنصر. معلمة اختيارية. |
| stroke | لون الحد أو الطلاء أو معرف خادم الطلاء للعنصر. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر الفلتر الأولي. معلمة اختيارية. |
| extend | إجراء اختياري لمزيد من تكوين SVGFEConvolveMatrixElementBuilder. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* enum [EdgeMode](../../edgemode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
