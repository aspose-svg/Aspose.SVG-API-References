---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGAngle ConvertToSpecifiedUnits. تحتفظ بنفس القيمة المخزنة الأساسية ولكن تعيد تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجةً لهذه الطريقة."
type: docs
weight: 50
url: /ar/net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

حافظ على القيمة المخزنة الأساسية نفسها، ولكن أعد ضبط معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجةً لهذه الطريقة.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة للتحويل إليه (مثال: SVG_ANGLETYPE_DEG). |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الكود [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_ANGLETYPE_UNKNOWN أو ليس ثابت وحدة صالح (أحد الثوابت الأخرى SVG_ANGLETYPE_* المعرفة في هذه الواجهة). |
| [DOMException](../../../aspose.svg.dom/domexception/) | الكود [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) يُرفع عندما تتطابق الزاوية مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
