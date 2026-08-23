---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddRadialGradient. تضيف تكوين عنصر radialGradient إلى المُنشئ."
type: docs
weight: 440
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

يضيف تكوين عنصر 'radialGradient' إلى المُنشئ.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'radialGradient'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

يضيف عنصر 'radialGradient' إلى مُنشئ SVG، محددًا مركزه، نصف قطره، ونقاط البؤرة، إلى جانب خصائص التدرج الأخرى.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'radialGradient'. |
| cx | الإحداثي السيني لمركز التدرج. يمكن أن يكون قيمة مزدوجة أو ValueTuple مع LengthType. معلمة اختيارية. |
| cy | الإحداثي الصادي لمركز التدرج. يمكن أن يكون قيمة مزدوجة أو ValueTuple مع LengthType. معلمة اختيارية. |
| r | نصف قطر التدرج. يمكن أن يكون قيمة مزدوجة أو ValueTuple مع LengthType. معلمة اختيارية. |
| fx | الإحداثي السيني لنقطة التركيز في التدرج. يمكن أن يكون قيمة مزدوجة أو ValueTuple مع LengthType. معلمة اختيارية. |
| fy | الإحداثي ص لنقطة التركيز في التدرج. يمكن أن يكون من نوع double أو ValueTuple مع LengthType. معلمة اختيارية. |
| gradientUnits | يحدد نظام الإحداثيات للتدرج. معلمة اختيارية. |
| spreadMethod | يحدد كيفية انتشار التدرج خارج نقاط البداية والنهاية. معلمة اختيارية. |
| href | المرجع إلى تدرج آخر، إذا كان ذلك مناسبًا. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر التدرج. معلمة اختيارية. |
| extend | إجراء اختياري لمزيد من تكوين منشئ عنصر التدرج الشعاعي. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
