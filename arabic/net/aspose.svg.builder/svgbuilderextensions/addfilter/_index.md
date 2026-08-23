---
title: "SVGBuilderExtensions.AddFilter"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddFilter. تُضيف تكوين عنصر filter إلى المُنشئ."
type: docs
weight: 300
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

يضيف تكوين عنصر 'filter' إلى المُنشئ.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'filter'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

يضيف عنصر 'filter' إلى مُنشئ SVG، مُعرّفًا تأثير فلتر يمكن تطبيقه على عناصر SVG.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'filter'. |
| filterUnits | يحدد نظام الإحداثيات لسمات x و y والعرض والارتفاع للمرشح. معلمة اختيارية. |
| primitiveUnits | يحدد نظام الإحداثيات لسمات العناصر الفرعية للمرشح. معلمة اختيارية. |
| x | إحداثي x لمنطقة المرشح. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| y | إحداثي y لمنطقة المرشح. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| width | عرض منطقة المرشح. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| height | ارتفاع منطقة المرشح. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. معلمة اختيارية. |
| fill | لون التعبئة أو الطلاء لعنصر المرشح. معلمة اختيارية. |
| stroke | لون الحد أو الطلاء لعنصر المرشح. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر المرشح. معلمة اختيارية. |
| extend | إجراء اختياري لمزيد من تكوين SVGFilterElementBuilder. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
