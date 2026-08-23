---
title: "SVGBuilderExtensions.Fill"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions Fill. تُعيّن سمة fill التي تُحدّد كيف يجب أن تُطبق الرسوم المتحركة الأنماط خارج مدتها النشطة"
type: docs
weight: 810
url: /ar/net/aspose.svg.builder/svgbuilderextensions/fill/
---
## Fill<TBuilder>(*this TBuilder, [AnimationFill](../../animationfill/)*) {#fill}

يضبط خاصية 'fill'، معرفًا كيفية تطبيق الرسوم المتحركة للأنماط خارج مدتها النشطة.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, AnimationFill value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | سلوك التعبئة في الرسوم المتحركة. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [AnimationFill](../../animationfill/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#fill_2}

يضبط خاصية 'fill' لعنصر SVG باستخدام تكوين مخصص.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | مفوض لتكوين PaintBuilder. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Color*) {#fill_3}

يضبط خاصية 'fill' لعنصر SVG باستخدام لون.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| color | اللون لتعيينه كملء. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#fill_1}

يضبط خاصية 'fill' لعنصر SVG باستخدام قيمة تعداد Paint معرفة مسبقًا.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| paint | قيمة تعداد Paint لتعيينها. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
