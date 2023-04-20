---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.SVG لمرجع .NET API
description: SVGLength طريقة. إعادة تعيين القيمة كرقم مع نوع الوحدة المرتبط  وبالتالي استبدال القيم لجميع السمات الموجودة على الكائن.
type: docs
weight: 60
url: /ar/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

إعادة تعيين القيمة كرقم مع نوع الوحدة المرتبط ، وبالتالي استبدال القيم لجميع السمات الموجودة على الكائن.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة للقيمة. |
| valueInSpecifiedUnits | Single | القيمة الجديدة .. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | كود[`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) يتم رفعه إذا كان نوع الوحدة هو SVG_LENGTHTYPE_UNKNOWN أو أنه ليس ثابت نوع وحدة صالح (أحد ثوابت SVG_LENGTHTYPE_ * الأخرى المحددة في هذه الواجهة) . |
| [DOMException](../../../aspose.svg.dom/domexception/) | كود[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) تُرفع عندما يتوافق الطول مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### أنظر أيضا

* class [SVGLength](../)
* مساحة الاسم [Aspose.Svg.DataTypes](../../svglength/)
* المجسم [Aspose.SVG](../../../)


