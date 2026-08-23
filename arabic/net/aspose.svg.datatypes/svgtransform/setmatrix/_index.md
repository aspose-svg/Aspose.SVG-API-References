---
title: "SVGTransform.SetMatrix"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGTransform SetMatrix. تُعيّن نوع التحويل إلى SVG_TRANSFORM_MATRIX مع المعامل matrix الذي يحدد التحويل الجديد. القيم من المعامل matrix تُنسخ؛ معامل matrix لا يستبدل SVGTransformmatrix"
type: docs
weight: 40
url: /ar/net/aspose.svg.datatypes/svgtransform/setmatrix/
---
## SVGTransform.SetMatrix method

يضبط نوع التحويل إلى SVG_TRANSFORM_MATRIX، مع المعامل matrix الذي يحدد التحويل الجديد. تُنسخ القيم من معامل matrix، ولا يستبدل معامل matrix الخاص بـ SVGTransform::matrix.

```csharp
public void SetMatrix(SVGMatrix matrix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | SVGMatrix | المصفوفة الجديدة للتحويل. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). يُثار عند محاولة تغيير قيمة سمة للقراءة فقط. |

### انظر أيضًا

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
