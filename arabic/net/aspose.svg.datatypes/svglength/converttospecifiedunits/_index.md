---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGLength ConvertToSpecifiedUnits. تحتفظ بنفس القيمة المخزنة الأساسية ولكن تعيد تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل خصائص الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجة لهذه الطريقة. على سبيل المثال إذا كانت القيمة الأصلية 0.5cm وتم استدعاء الطريقة للتحويل إلى مليمترات فإن unitType سيتغير إلى SVG_LENGTHTYPE_MM و valueInSpecifiedUnits سيتحول إلى القيمة الرقمية 5 و valueAsString سيتحول إلى 5mm."
type: docs
weight: 50
url: /ar/net/aspose.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

حافظ على نفس القيمة المخزنة الأساسية، ولكن أعد تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجة لهذه الطريقة. على سبيل المثال، إذا كانت القيمة الأصلية "0.5cm" وتم استدعاء الطريقة للتحويل إلى مليمترات، فإن unitType سيتغير إلى SVG_LENGTHTYPE_MM، و valueInSpecifiedUnits سيتغير إلى القيمة العددية 5، و valueAsString سيتغير إلى "5mm".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة للتحويل إليه (مثال: SVG_LENGTHTYPE_MM). |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_LENGTHTYPE_UNKNOWN أو ليس ثابت وحدة صالح (أحد الثوابت الأخرى SVG_LENGTHTYPE_* المعرفة في هذه الواجهة). |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) يُرفع عندما يتطابق الطول مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
