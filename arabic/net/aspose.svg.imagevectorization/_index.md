---
title: "Aspose.Svg.ImageVectorization"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "تحتوي مساحة الاسم Aspose.Svg.ImageVectorization على فئات لتحويل الصور النقطية إلى رسومات متجهية وتحويلها إلى مستندات SVG. تتضمن هذه العملية تقليل الصور النقطية إلى أشكال هندسية مكوّنة من عناصر المسار وتخزينها كـ SVG. تشمل مساحة الاسم فئات لبناء مقاطع المسار وتبسيط ونقّح نقاط التتبع وتكوين خيارات التحويل المتجهية."
type: docs
weight: 190
url: /ar/net/aspose.svg.imagevectorization/
---
تحتوي مساحة الاسم **Aspose.Svg.ImageVectorization** على فئات لتوجيه الصور النقطية وتحويلها إلى مستندات SVG. تشمل هذه العملية تقليل ملفات البت ماب إلى أشكال هندسية مكوّنة من عناصر المسار وتخزينها كملفات SVG. تتضمن مساحة الاسم فئات لبناء مقاطع المسار، وتبسيط وتنعيم نقاط التتبع، وتكوين خيارات التوجيه.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [BezierPathBuilder](./bezierpathbuilder/) | الفئة [`BezierPathBuilder`](../aspose.svg.imagevectorization/bezierpathbuilder/) مسؤولة عن إنشاء مسار بيزير من مجموعة نقاط معينة. تقرب تتبع النقاط بمنحنى بيزير، وتُحسّن عدد المقاطع لتطابق التتبع الأصلي بأقرب شكل مع تقليل التعقيد. |
| [ImageTraceSimplifier](./imagetracesimplifier/) | الفئة ImageTraceSimplifier مسؤولة عن تقليل عدد النقاط في منحنى يتم تقريبها بسلسلة من نقاط التتبع. |
| [ImageTraceSmoother](./imagetracesmoother/) | الفئة ImageTraceSimplifier مسؤولة عن تنعيم عدد النقاط في منحنى يتم تقريبها بسلسلة من نقاط التتبع. تُطبق هذه الفئة نهج أقرب جار. |
| [ImageVectorizer](./imagevectorizer/) | هذه الفئة ImageVectorizer تقوم بتحويل الصور النقطية مثل PNG و JPG و GIF و BMP وغيرها... وتعيد كائن SVGDocument. تحت مفهوم التحويل نقصد عملية تقليل الصور النقطية إلى أشكال هندسية مكوّنة من عناصر المسار وتُخزن كـ SVG. |
| [ImageVectorizerConfiguration](./imagevectorizerconfiguration/) | الفئة [`ImageVectorizerConfiguration`](../aspose.svg.imagevectorization/imagevectorizerconfiguration/) تُعرّف تكوين طرق وخيارات تحويل الصور. يُستخدم التكوين لتهيئة كائن ImageVectorizer ويُوفر خيارات التكوين لتحويل الصور. |
| [SplinePathBuilder](./splinepathbuilder/) | الفئة [`SplinePathBuilder`](../aspose.svg.imagevectorization/splinepathbuilder/) مُصممة لبناء مسار ناعم عن طريق تحويل منحنيات Catmull–Rom المركزية إلى منحنيات بيزيه. تُقدّم طريقة لتوليد مسار يتداخل بسلاسة عبر مجموعة من النقاط، موفرةً توازناً بين الدقة للنقاط وسلاسة المنحنى. |
| [StencilConfiguration](./stencilconfiguration/) | الفئة [`StencilConfiguration`](../aspose.svg.imagevectorization/stencilconfiguration/) تُعرّف تكوين خيارات تأثير القالب. |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [IImageTraceSimplifier](./iimagetracesimplifier/) | واجهة IImageTraceSimplifier مسؤولة عن تقليل النقاط في التتبع. |
| [IImageTraceSmoother](./iimagetracesmoother/) | واجهة IImageTraceSmoother مسؤولة عن تنعيم التتبع. |
| [IPathBuilder](./ipathbuilder/) | واجهة IPathBuilder مسؤولة عن بناء مقاطع المسار [`SVGPathSeg`](../aspose.svg.paths/svgpathseg/) من قائمة نقاط التتبع. |
## التعداد

| التعداد | الوصف |
| --- | --- |
| [StencilType](./stenciltype/) | التعداد [`StencilType`](../aspose.svg.imagevectorization/stenciltype/) يُعرّف أنواع القوالب. |
