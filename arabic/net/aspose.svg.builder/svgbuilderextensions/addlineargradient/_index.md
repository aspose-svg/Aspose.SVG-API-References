---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddLinearGradient. تضيف تكوين عنصر linearGradient إلى المُنشئ."
type: docs
weight: 360
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

يضيف تكوين عنصر 'linearGradient' إلى المُنشئ.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'linearGradient'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

يضيف عنصر 'linearGradient' إلى مُنشئ SVG، محددًا مواضع البداية والنهاية، إلى جانب خصائص التدرج الأخرى.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'linearGradient'. |
| x1 | الإحداثي x الابتدائي للتدرج. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. |
| y1 | الإحداثي y الابتدائي للتدرج. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. |
| x2 | الإحداثي x النهائي للتدرج. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. |
| y2 | الإحداثي y النهائي للتدرج. يمكن أن يكون عددًا مزدوجًا أو ValueTuple مع LengthType. |
| gradientUnits | يحدد نظام الإحداثيات للتدرج. معلمة اختيارية. |
| spreadMethod | يحدد كيفية انتشار التدرج خارج نقاط البداية والنهاية. معلمة اختيارية. |
| href | المرجع إلى تدرج آخر، إذا كان ذلك مناسبًا. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر التدرج. معلمة اختيارية. |
| extend | إجراء اختياري لتكوين إضافي لمُنشئ عنصر التدرج الخطي. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
