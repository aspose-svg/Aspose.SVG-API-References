---
title: "فئة SVGMatrix"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.DataTypes.SVGMatrix. العديد من عمليات الرسومات في SVG تستخدم مصفوفات 2x3 بالشكل a c e b d f والتي عند توسيعها إلى مصفوفة 3x3 لأغراض الحسابات المصفوفية تصبح a c e b d f 0 0 1."
type: docs
weight: 2230
url: /ar/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

تستخدم العديد من عمليات رسومات SVG مصفوفات 2x3 بالشكل: [a c e] [b d f] والتي، عند توسيعها إلى مصفوفة 3x3 لأغراض حساب المصفوفات، تصبح: [a c e] [b d f] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | المكوّن A للمصفوفة. |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | المكوّن B للمصفوفة. |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | المكوّن C للمصفوفة. |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | المكوّن D للمصفوفة. |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | المكوّن E للمصفوفة. |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | المكوّن F للمصفوفة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و- اختياريًا - المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(*SVGMatrix*) | يُجري ضربًا مصفوفيًا. تُضرب هذه المصفوفة بعديًا بمصفوفة أخرى، مما يُعيد المصفوفة الجديدة الناتجة. |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(*float*) | يضرب بعديًا تحويل دوران على المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(*float*) | يضرب بعديًا تحويل مقياس موحد على المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(*float, float*) | يُضيف بعد الضرب تحويل مقياس غير متساوٍ إلى المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(*float*) | يُضيف بعد الضرب تحويل انحراف X إلى المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(*float*) | يُضيف بعد الضرب تحويل انحراف Y إلى المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(*float, float*) | يُضيف بعد الضرب تحويل إزاحة إلى المصفوفة الحالية ويُعيد المصفوفة الناتجة. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
