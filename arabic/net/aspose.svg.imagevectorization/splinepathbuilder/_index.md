---
title: "فئة SplinePathBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.ImageVectorization.SplinePathBuilder. تم تصميم فئة SplinePathBuilder لإنشاء مسار ناعم عن طريق تحويل منحنيات CatmullRom المركزية إلى منحنيات بيزيه. توفر طريقة لتوليد مسار يتداخل بسلاسة عبر مجموعة من النقاط، مقدمةً توازنًا بين الدقة في تمثيل النقاط وسلاسة المنحنى."
type: docs
weight: 4230
url: /ar/net/aspose.svg.imagevectorization/splinepathbuilder/
---
## SplinePathBuilder class

تم تصميم فئة `SplinePathBuilder` لإنشاء مسار ناعم عن طريق تحويل منحنيات Catmull–Rom المركزية إلى منحنيات بيزيه. توفر طريقة لتوليد مسار يتداخل بسلاسة عبر مجموعة من النقاط، مقدمةً توازنًا بين الدقة في تمثيل النقاط وسلاسة المنحنى.

```csharp
public class SplinePathBuilder : IPathBuilder
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SplinePathBuilder](splinepathbuilder/#constructor)() | يُنشئ مثيلًا جديدًا من فئة `SplinePathBuilder`. |
| [SplinePathBuilder](splinepathbuilder/#constructor_2)(*float*) | يُنشئ مثيلًا جديدًا من فئة `SplinePathBuilder`. |
| [SplinePathBuilder](splinepathbuilder/#constructor_1)(*[IImageTraceSmoother](../iimagetracesmoother/), [IImageTraceSimplifier](../iimagetracesimplifier/), float*) | يُنشئ مثيلًا جديدًا من فئة `SplinePathBuilder`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/splinepathbuilder/tension/) { get; set; } | قيمة التوترات تؤثر على مدى حدة انحناء المنحنى عند نقاط التحكم (interpolated). يجب أن تكون في النطاق من 0 إلى 1. أي قيم أعلى أو أقل سيتم محاذاتها مع القيم الدنيا والعليا لهذا النطاق، وفقًا لذلك. |
| [TraceSimplifier](../../aspose.svg.imagevectorization/splinepathbuilder/tracesimplifier/) { get; set; } | يحصل أو يعيّن مبسط الأثر. |
| [TraceSmoother](../../aspose.svg.imagevectorization/splinepathbuilder/tracesmoother/) { get; set; } | يحصل أو يعيّن مملّس الأثر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/splinepathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | يبني مسارًا سلسًا عبر تسلسل من النقاط عن طريق تحويل منحنيات Centripetal Catmull–Rom إلى منحنيات Bezier. تضمن هذه الطريقة انتقالًا طبيعيًا وسلسًا عبر كل نقطة، وتُنشئ مسار SVG يتبع الأثر المقدم بدقة. |

### انظر أيضًا

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
