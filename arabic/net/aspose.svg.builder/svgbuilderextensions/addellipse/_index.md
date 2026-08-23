---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddEllipse. تضيف تكوين عنصر إهليلجي إلى الباني."
type: docs
weight: 120
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

يضيف تكوين عنصر 'ellipse' إلى الباني.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'ellipse'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

يضيف عنصر 'ellipse' إلى باني SVG، مع تحديد مركزه، نصف القطرين، والأنماط.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل باني SVG الذي سيُضاف إليه عنصر 'ellipse'. |
| cx | الإحداثي السيني لمركز الإهليلج. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| cy | الإحداثي الصادي لمركز الإهليلج. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| rx | نصف القطر السيني للإهليلج. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| ry | نصف القطر الصادي للإهليلج. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| fill | لون التعبئة أو نمط الطلاء للإهليلج. يمكن أن يكون Color أو قيمة تعداد Paint أو معرف خادم الطلاء. معامل اختياري. |
| stroke | لون الحد أو نمط الطلاء للإهليلج. يمكن أن يكون Color أو قيمة تعداد Paint أو معرف خادم الطلاء. معامل اختياري. |
| معرّف | المعرّف الفريد لعنصر الإهليلج. معامل اختياري. |
| extend | إجراء اختياري إضافي لتكوين باني عنصر الإهليلج بشكل أعمق. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
