---
title: "فئة BezierPathBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.ImageVectorization.BezierPathBuilder. فئة BezierPathBuilder مسؤولة عن إنشاء مسار Bezier من مجموعة نقاط معينة. تقرّب الأثر من النقاط باستخدام منحنى Bezier مع تحسين عدد القطاعات لتطابق الأثر الأصلي بدقة مع تقليل التعقيد."
type: docs
weight: 4150
url: /ar/net/aspose.svg.imagevectorization/bezierpathbuilder/
---
## BezierPathBuilder class

الفئة `BezierPathBuilder` مسؤولة عن إنشاء مسار بيزيير من مجموعة نقاط معينة. إنها تقرب تتبع النقاط بمنحنى بيزيير، مع تحسين عدد القطاعات لتطابق التتبع الأصلي عن كثب مع تقليل التعقيد.

```csharp
public class BezierPathBuilder : IPathBuilder
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [BezierPathBuilder](bezierpathbuilder/)() | ينشئ مثيلاً جديداً للفئة `BezierPathBuilder`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ErrorThreshold](../../aspose.svg.imagevectorization/bezierpathbuilder/errorthreshold/) { get; set; } | يحصل أو يضبط عتبة الخطأ. هذا المعامل يحدد الحد الأقصى لانحراف النقاط عن المنحنى الملائم. بشكل افتراضي قيمته 30. |
| [MaxIterations](../../aspose.svg.imagevectorization/bezierpathbuilder/maxiterations/) { get; set; } | يحصل أو يضبط عتبة الخطأ. هذا المعامل يحدد عدد التكرارات لطريقة تقريب المربعات الصغرى. بشكل افتراضي قيمته 30. |
| [TraceSmoother](../../aspose.svg.imagevectorization/bezierpathbuilder/tracesmoother/) { get; set; } | يحصل أو يعيّن مملّس الأثر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/bezierpathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | يبني مسار بيزيير محسّن من تسلسل نقاط التتبع. الطريقة تقرب التتبع المعطى بمنحنى بيزيير، باستخدام مزيج من قطاعات الخط والمنحنى. تهدف إلى تقليل عدد القطاعات مع ضمان أن المسار يطابق التتبع الأصلي عن كثب. |

### انظر أيضًا

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
