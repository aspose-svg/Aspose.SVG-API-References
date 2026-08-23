---
title: "فئة SVGPoint"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.DataTypes.SVGPoint. العديد من واجهات SVG DOM تشير إلى كائنات من فئة SVGPoint. الـ SVGPoint هو زوج إحداثيات x y. عند استخدامها في عمليات المصفوفات يُعامل الـ SVGPoint كمتجه على الشكل x y 1. إذا تم تعيين كائن SVGRect كقراءة فقط، فإن محاولة تعديل أحد سماته ستؤدي إلى رمي استثناء."
type: docs
weight: 2260
url: /ar/net/aspose.svg.datatypes/svgpoint/
---
## SVGPoint class

تشير العديد من واجهات DOM الخاصة بـ SVG إلى كائنات من الفئة SVGPoint. الـ SVGPoint هو زوج إحداثيات (x, y). عند استخدامها في عمليات المصفوفة، يُعامل SVGPoint كمتجه بالشكل: [x] [y] [1] إذا تم تعيين كائن SVGRect كقراءة فقط، فإن محاولة تعيين أحد سماته ستؤدي إلى رمي استثناء.

```csharp
public class SVGPoint : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [X](../../aspose.svg.datatypes/svgpoint/x/) { get; set; } | إحداثي X. |
| [Y](../../aspose.svg.datatypes/svgpoint/y/) { get; set; } | إحداثي Y. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و- اختياريًا - المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [MatrixTransform](../../aspose.svg.datatypes/svgpoint/matrixtransform/)(*[SVGMatrix](../svgmatrix/)*) | يطبق تحويل مصفوفة 2x3 على كائن SVGPoint هذا ويعيد كائن SVGPoint جديدًا محوَّلاً: newpoint = matrix* thispoint |
| override [ToString](../../aspose.svg.datatypes/svgpoint/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
