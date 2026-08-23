---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddPolygon. تضيف تكوين عنصر مضلع إلى المُنشئ"
type: docs
weight: 420
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

يضيف تكوين عنصر 'polygon' إلى المُنشئ.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'polygon'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

يضيف عنصر 'polygon' إلى مُنشئ SVG، محددًا رؤوسه، والأنماط.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'polygon'. |
| نقاط | مصفوفة من القيم المزدوجة تمثل نقاط المضلع (إحداثيات x و y بالتناوب). |
| fill | لون التعبئة أو نمط الرسم للمضلع. يمكن أن يكون قيمة من نوع Color أو Paint enum أو معرف خادم الرسم. معامل اختياري. |
| stroke | لون الحد أو نمط الرسم للمضلع. يمكن أن يكون قيمة من نوع Color أو Paint enum أو معرف خادم الرسم. معامل اختياري. |
| معرّف | المعرف الفريد لعنصر المضلع. معامل اختياري. |
| extend | إجراء اختياري لتكوين إضافي لمُنشئ عنصر المضلع. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
