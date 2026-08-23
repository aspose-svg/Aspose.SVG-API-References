---
title: "SVGBuilderExtensions.AddPattern"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddPattern. تضيف تكوين عنصر نمط إلى المُنشئ."
type: docs
weight: 410
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addpattern/
---
## AddPattern<TBuilder>(*this TBuilder, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern}

يضيف تكوين عنصر 'pattern' إلى المُنشئ.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, 
    Action<SVGPatternElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'pattern'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPattern<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, string, string, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern_1}

يضيف عنصر 'pattern' إلى مُنشئ SVG، محددًا نظام الإحداثيات والوحدات لمحتوى النمط.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, CoordinateUnits? patternUnits, 
    CoordinateUnits? patternContentUnits, string href = null, string id = null, 
    Action<SVGPatternElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG، مما يُسهل استخدام واجهة برمجة التطبيقات السلسة. |
| builder | مثيل مُنشئ SVG الذي سيُضاف إليه عنصر 'pattern'. |
| patternUnits | يحدد نظام الإحداثيات للنمط. معلمة اختيارية. |
| patternContentUnits | يحدد نظام الإحداثيات للمحتوى داخل النمط. معلمة اختيارية. |
| href | المرجع إلى نمط آخر، إذا كان ذلك مناسبًا. معلمة اختيارية. |
| معرّف | المعرّف الفريد لعنصر النمط. معلمة اختيارية. |
| extend | إجراء اختياري لمزيد من تكوين مُنشئ عنصر النمط. |

### قيمة الإرجاع

مثيل الباني، يسمح بسلسلة الأساليب.

### انظر أيضًا

* enum [CoordinateUnits](../../coordinateunits/)
* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
