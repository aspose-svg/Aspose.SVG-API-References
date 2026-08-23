---
title: "SVGGeometryElement.Combine"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Combine لـ SVGGeometryElement. تجمع هذه الهندسة مع هندسة SVG أخرى باستخدام عملية منطقية وتُعيد عنصر مسار جديد يحتوي على النتيجة."
type: docs
weight: 20
url: /ar/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

يجمع هذه الهندسة مع هندسة SVG أخرى باستخدام عملية منطقية، ويعيد عنصر `<path>` جديد يحتوي على النتيجة.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | الهندسة الأخرى التي سيتم الجمع معها. يجب أن تكون في نفس المستند. |
| op | BooleanPathOp | المعامل المنطقي المراد تطبيقه: Union (A UNION B)، Difference (A - B)، Intersection (A INTERSECT B)، أو Exclusion (XOR). |

### قيمة الإرجاع

[`SVGPathElement`](../../svgpathelement/) جديد يكون سمة `d` الخاصة به تشفر النتيجة في مساحة المستخدم الجذرية `<svg>` (بكسل CSS). العنصر لا يُضاف إلى DOM.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرفع إذا كان *geometryElement* null. |
| InvalidOperationException | يتم إلقاؤه إذا لم يكن لهذا العنصر مستند مالك. |
| NotSupportedException | يتم إلقاؤه عندما تكون عمليات المسار المنطقية غير متوفرة؛ هذه الميزة تتطلب الخلفية SkiaSharp (قم بتثبيت حزمة Aspose.SVG.Drawing.SkiaSharp). |

### انظر أيضًا

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
