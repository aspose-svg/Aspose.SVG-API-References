---
title: "SVGBuilderExtensions.Points"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions Points. تُعيّن سمة points لعنصر SVG باستخدام مصفوفة من القيم المزدوجة"
type: docs
weight: 1910
url: /ar/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

يضبط سمة 'points' لعنصر SVG باستخدام مصفوفة من القيم المزدوجة.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| نقاط | مصفوفة من القيم المزدوجة تمثل النقاط (يجب أن تكون عددًا زوجيًا). |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى استثناء إذا تم توفير عدد فردي من النقاط. |

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

يضبط سمة 'points' لعنصر SVG باستخدام مصفوفة من كائنات PointF.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| نقاط | مصفوفة من كائنات PointF تمثل النقاط. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
