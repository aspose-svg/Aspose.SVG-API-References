---
title: "SplinePathBuilder.Build"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SplinePathBuilder Build. تُنشئ مسارًا سلسًا عبر تسلسل من النقاط عن طريق تحويل منحنيات Centripetal CatmullRom إلى منحنيات Bezier. تضمن هذه الطريقة انتقالًا طبيعيًا وسلسًا عبر كل نقطة، مُنشئةً مسار SVG يتبع بدقة الأثر المقدم."
type: docs
weight: 50
url: /ar/net/aspose.svg.imagevectorization/splinepathbuilder/build/
---
## SplinePathBuilder.Build method

يبني مسارًا سلسًا عبر تسلسل من النقاط عن طريق تحويل منحنيات Centripetal Catmull–Rom إلى منحنيات Bezier. تضمن هذه الطريقة انتقالًا طبيعيًا وسلسًا عبر كل نقطة، وتُنشئ مسار SVG يتبع الأثر المقدم بدقة.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الأثر | IEnumerable`1 | تسلسل النقاط التي سيتم استيفاؤها في مسار سلس. |

### قيمة الإرجاع

سلسلة تمثل بيانات مسار SVG، تتضمن أوامر منحنى Bezier وإحداثيات تقرب من منحنى Centripetal Catmull–Rom.

### انظر أيضًا

* class [SplinePathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
