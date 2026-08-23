---
title: "SVGBuilderExtensions.AddRect"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddRect. تضيف تكوين عنصر rect إلى المُنشئ."
type: docs
weight: 450
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

يضيف تكوين عنصر 'rect' إلى المُنشئ.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'rect'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

يضيف عنصر 'rect' (مستطيل) بأبعاد وأنماط محددة إلى مُنشئ SVG.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'rect'. |
| x | الإحداثي السيني لنقطة بدء المستطيل. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| y | الإحداثي الصادي لنقطة بدء المستطيل. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| width | عرض المستطيل. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| height | ارتفاع المستطيل. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| fill | لون التعبئة أو نمط الرسم للمستطيل. يمكن أن يكون Color أو قيمة تعداد Paint أو معرف خادم الرسم. معلمة اختيارية. |
| stroke | لون الحد أو نمط الرسم لحدود المستطيل. يمكن أن يكون Color أو قيمة تعداد Paint أو معرف خادم الرسم. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر المستطيل. معلمة اختيارية. |
| extend | إجراء اختياري لمزيد من تكوين منشئ عنصر المستطيل. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
