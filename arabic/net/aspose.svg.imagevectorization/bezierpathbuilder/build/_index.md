---
title: "BezierPathBuilder.Build"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة BezierPathBuilder Build. تُنشئ مسار Bezier مُحسّن من تسلسل نقاط التتبع. تُقرب الطريقة التتبع المُعطى بمنحنى Bezier باستخدام مزيج من مقاطع الخط والمنحنى. تهدف إلى تقليل عدد المقاطع مع ضمان أن يتطابق المسار بشكل وثيق مع التتبع الأصلي"
type: docs
weight: 50
url: /ar/net/aspose.svg.imagevectorization/bezierpathbuilder/build/
---
## BezierPathBuilder.Build method

يبني مسار بيزيير محسّن من تسلسل نقاط التتبع. الطريقة تقرب التتبع المعطى بمنحنى بيزيير، باستخدام مزيج من قطاعات الخط والمنحنى. تهدف إلى تقليل عدد القطاعات مع ضمان أن المسار يطابق التتبع الأصلي عن كثب.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الأثر | IEnumerable`1 | التسلسل من النقاط التي تُعرّف التتبع المراد تقريبه. |

### قيمة الإرجاع

سلسلة تمثّل بيانات مسار SVG. تتكوّن هذه البيانات من سلسلة من الأوامر والإحداثيات التي تُعرّف مسار Bezier، مُقربةً التتبع المدخل بشكل وثيق مع تقليل التعقيد.

### انظر أيضًا

* class [BezierPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
