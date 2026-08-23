---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة NewValueSpecifiedUnits لـ SVGLength. تعيد تعيين القيمة كرقم مع نوع وحدة مرتبط، وبالتالي تستبدل القيم لجميع الخصائص على الكائن"
type: docs
weight: 60
url: /ar/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

أعد ضبط القيمة كرقم مع unitType المرتبط، وبالتالي استبدال القيم لجميع السمات على الكائن.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة للقيمة. |
| valueInSpecifiedUnits | Single | القيمة الجديدة.. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_LENGTHTYPE_UNKNOWN أو ليس ثابت وحدة صالح (أحد الثوابت الأخرى SVG_LENGTHTYPE_* المعرفة في هذه الواجهة). |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) يُرفع عندما يتطابق الطول مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
