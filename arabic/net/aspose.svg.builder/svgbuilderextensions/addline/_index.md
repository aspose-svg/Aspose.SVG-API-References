---
title: "SVGBuilderExtensions.AddLine"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddLine. تضيف تكوين عنصر خط إلى المُنشئ."
type: docs
weight: 350
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

يضيف تكوين عنصر 'line' إلى المُنشئ.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'line'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

يضيف عنصر 'line' بنقاط بداية ونهاية محددة، وأنماط إلى مُنشئ SVG.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'line'. |
| x1 | الإحداثي x لنقطة بداية الخط. يمكن أن يكون قيمة مزدوجة أو زوجًا من القيمة المزدوجة وLengthType. |
| y1 | الإحداثي y لنقطة بداية الخط. يمكن أن يكون قيمة مزدوجة أو زوجًا من القيمة المزدوجة وLengthType. |
| x2 | الإحداثي x لنقطة نهاية الخط. يمكن أن يكون قيمة مزدوجة أو زوجًا من القيمة المزدوجة وLengthType. |
| y2 | الإحداثي y لنقطة نهاية الخط. يمكن أن يكون قيمة مزدوجة أو زوجًا من القيمة المزدوجة وLengthType. |
| fill | لون التعبئة أو نمط الطلاء للخط. يمكن أن يكون Color أو قيمة من تعداد Paint أو معرف خادم الطلاء. معامل اختياري. |
| stroke | لون الحد أو نمط الطلاء للخط. يمكن أن يكون Color أو قيمة من تعداد Paint أو معرف خادم الطلاء. معامل اختياري. |
| معرّف | المعرّف الفريد لعنصر الخط. معامل اختياري. |
| extend | إجراء اختياري لمزيد من تكوين مُنشئ عنصر الخط. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
