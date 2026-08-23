---
title: "SVGBuilderExtensions.AddFeComposite"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "SVGBuilderExtensions AddFeComposite method. تضيف تكوين عنصر feComposite إلى المُنشئ. هذا العنصر يُجري دمجًا بتّيًا بين رسومات إدخالٍ اثنتين."
type: docs
weight: 160
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addfecomposite/
---
## AddFeComposite<TBuilder>(*this TBuilder, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite}

يضيف تكوين عنصر 'feComposite' إلى الباني. يقوم هذا العنصر بدمج ثنائي للرسومتين المدخلتين.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    Action<SVGFECompositeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'feComposite'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComposite<TBuilder>(*this TBuilder, CompositeOperator?, double?, double?, double?, double?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite_1}

يضيف عنصر 'feComposite' إلى منشئ SVG، محددًا عملية التركيب ومجموعة متنوعة من الخصائص الأخرى لدمج الصور المدخلة.

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

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'feComposite'. |
| compositeOperator | عامل التركيب الذي سيُستخدم. معلمة اختيارية. |
| k1 | القيمة الرقمية الأولى لعملية التركيب. معلمة اختيارية. |
| k2 | القيمة الرقمية الثانية لعملية التركيب. معلمة اختيارية. |
| k3 | القيمة الرقمية الثالثة لعملية التركيب. معلمة اختيارية. |
| k4 | القيمة الرقمية الرابعة لعملية التركيب. معلمة اختيارية. |
| in | الإدخال الأول لتأثير التركيب. يمكن أن يكون سلسلة نصية أو FilterInput. معلمة اختيارية. |
| in2 | الإدخال الثاني لتأثير التركيب. يمكن أن يكون سلسلة نصية أو FilterInput. معلمة اختيارية. |
| result | معرّف النتيجة لهذا العنصر الأساسي للمرشح. معلمة اختيارية. |
| x | الإحداثي السيني لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| y | الإحداثي الصادي لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| width | العرض لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| height | الارتفاع لمنطقة الفلتر الأولية الفرعية. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| fill | لون التعبئة أو الطلاء أو معرف خادم الطلاء للعنصر. معلمة اختيارية. |
| stroke | لون الحد أو الطلاء أو معرف خادم الطلاء للعنصر. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر الفلتر الأولي. معلمة اختيارية. |
| extend | إجراء اختياري لمزيد من تكوين SVGFECompositeElementBuilder. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

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
