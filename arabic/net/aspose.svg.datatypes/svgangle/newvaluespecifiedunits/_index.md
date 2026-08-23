---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGAngle NewValueSpecifiedUnits. تعيد ضبط القيمة كعدد مع unitType المرتبط، مما يستبدل القيم لجميع السمات على الكائن."
type: docs
weight: 60
url: /ar/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

أعد ضبط القيمة كرقم مع unitType المرتبط، وبالتالي استبدال القيم لجميع السمات على الكائن.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newUnitType | UInt16 | نوع الوحدة للقيمة (مثال: SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | قيمة الزاوية. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الكود [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_ANGLETYPE_UNKNOWN أو ليس ثابت وحدة صالح (أحد الثوابت الأخرى SVG_ANGLETYPE_* المعرفة في هذه الواجهة). |
| [DOMException](../../../aspose.svg.dom/domexception/) | الكود [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) يُرفع عندما تتطابق الزاوية مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
