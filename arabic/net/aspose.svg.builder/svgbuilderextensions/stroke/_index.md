---
title: "SVGBuilderExtensions.Stroke"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions Stroke. تعيين سمة stroke لعنصر SVG باستخدام تكوين طلاء مخصص."
type: docs
weight: 2080
url: /ar/net/aspose.svg.builder/svgbuilderextensions/stroke/
---
## Stroke<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#stroke_1}

يضبط خاصية 'stroke' لعنصر SVG باستخدام تكوين طلاء مخصص.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | مفوض لتكوين الطلاء. |

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

## Stroke<TBuilder>(*this TBuilder, Color*) {#stroke_2}

يضبط خاصية 'stroke' لعنصر SVG باستخدام لون محدد.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| color | اللون المستخدم للـ stroke. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#stroke}

يضبط خاصية 'stroke' لعنصر SVG باستخدام قيمة طلاء مسبقة التعريف.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| paint | قيمة الطلاء التي سيتم تعيينها. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
