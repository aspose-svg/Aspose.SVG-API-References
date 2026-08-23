---
title: "واجهة IMatrix"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Drawing.IMatrix. تمثل مصفوفة تُستخدم للتحويلات."
type: docs
weight: 3500
url: /ar/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

يمثل مصفوفة تُستخدم للتحويلات.

```csharp
public interface IMatrix
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه المصفوفة هي مصفوفة الهوية. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه المصفوفة قابلة للعكس. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | يحصل على أو يضبط القيمة في الصف الأول والعمود الأول من المصفوفة. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | يحصل على أو يضبط القيمة في الصف الأول والعمود الثاني من المصفوفة. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | يحصل على أو يضبط القيمة في الصف الثاني والعمود الأول من المصفوفة. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | يحصل على أو يضبط القيمة في الصف الثاني والعمود الثاني من المصفوفة. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | يحصل على أو يضبط القيمة في الصف الثالث والعمود الأول من المصفوفة. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | يحصل على أو يضبط القيمة في الصف الثالث والعمود الثاني من المصفوفة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | ينشئ نسخة من هذه المصفوفة. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | يحصل على عناصر المصفوفة كمصفوفة. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | يعكس هذه المصفوفة. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | يضرب هذه المصفوفة بمصفوفة أخرى. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | يضرب هذه المصفوفة بمصفوفة أخرى بالترتيب المحدد. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | يعيد تعيين المصفوفة إلى مصفوفة الهوية. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | يدور المصفوفة بالزاوية المحددة. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | يدور المصفوفة بالزاوية المحددة بالترتيب المحدد. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | يدور المصفوفة بالزاوية المحددة حول النقطة المحددة. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | يدور المصفوفة بالزاوية المحددة حول النقطة المحددة بالترتيب المحدد. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | يقوم بتكبير المصفوفة بعوامل القياس المحددة بشكل موحد. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | يقوم بتكبير المصفوفة بعوامل القياس المحددة بالترتيب المحدد. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | يطبق تحويلًا مائلًا على المصفوفة. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | يحوّل النقطة المحددة باستخدام هذه المصفوفة. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | يحوّل مصفوفة من النقاط باستخدام هذه المصفوفة. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | يحوّل المستطيل المحدد باستخدام هذه المصفوفة. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | ينقل المصفوفة بالقيم الإزاحة المحددة. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | يُترجم المصفوفة بالقيم المحددة للإزاحة بالترتيب المحدد. |

### انظر أيضًا

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
