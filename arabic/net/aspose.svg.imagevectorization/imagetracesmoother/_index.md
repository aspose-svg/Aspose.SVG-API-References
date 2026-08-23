---
title: "فئة ImageTraceSmoother"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.ImageVectorization.ImageTraceSmoother. فئة ImageTraceSimplifier مسؤولة عن تنعيم عدد النقاط في منحنى يتم تقريبها بسلسلة من نقاط التتبع. هذه الفئة تُطبق نهج أقرب جار."
type: docs
weight: 4200
url: /ar/net/aspose.svg.imagevectorization/imagetracesmoother/
---
## ImageTraceSmoother class

الفئة ImageTraceSimplifier مسؤولة عن تنعيم عدد النقاط في منحنى يتم تقريبها بسلسلة من نقاط التتبع. تُطبق هذه الفئة نهج أقرب جار.

```csharp
public class ImageTraceSmoother : IImageTraceSmoother
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [ImageTraceSmoother](imagetracesmoother/#constructor)() | يقوم بإنشاء نسخة جديدة من الفئة `ImageTraceSmoother`. |
| [ImageTraceSmoother](imagetracesmoother/#constructor_1)(*int*) | يقوم بإنشاء نسخة جديدة من الفئة `ImageTraceSmoother`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extent](../../aspose.svg.imagevectorization/imagetracesmoother/extent/) { get; set; } | يحصل أو يحدد مدى المنطقة التي يُنظر إليها بواسطة نقطة الاستعلام. يجب أن يكون في النطاق من 1 إلى 20. أي قيم أعلى أو أقل سيتم تعديلها لتتناسب مع الحد الأدنى والحد الأقصى لهذا النطاق، وفقًا لذلك. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Smooth](../../aspose.svg.imagevectorization/imagetracesmoother/smooth/)(*IEnumerable&lt;PointF&gt;*) | ينعم التتبع. |

### انظر أيضًا

* interface [IImageTraceSmoother](../iimagetracesmoother/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
