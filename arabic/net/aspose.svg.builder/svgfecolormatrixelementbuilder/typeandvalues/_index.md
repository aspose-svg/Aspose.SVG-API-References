---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة TypeAndValues في SVGFEColorMatrixElementBuilder. تحدد سمتي type و values لعنصر feColorMatrix لتحديد عملية مصفوفة الألوان ومعلماتها"
type: docs
weight: 30
url: /ar/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

يضبط سمتي 'type' و 'values' لعنصر feColorMatrix، محددًا عملية مصفوفة الألوان ومعلماتها.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | ColorMatrixOperation | قيمة تعداد ColorMatrixOperation التي تمثل نوع عملية مصفوفة الألوان. |
| القيم | Double[] | معلمات عملية مصفوفة الألوان. |

### قيمة الإرجاع

مثيل الباني الحالي.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما لا تتطابق القيم المقدمة مع متطلبات النوع المحدد. |
| NotSupportedException | يُرمى عندما يتم توفير نوع عملية مصفوفة غير مدعوم. |

### انظر أيضًا

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
