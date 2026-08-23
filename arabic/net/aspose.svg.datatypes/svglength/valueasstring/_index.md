---
title: "SVGLength.ValueAsString"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "خاصية SVGLength ValueAsString. القيمة كسلسلة نصية بالوحدات التي يعبر عنها unitType. ضبط هذه الخاصية سيؤدي إلى تحديث value و valueInSpecifiedUnits و unitType تلقائيًا لتعكس هذا الإعداد."
type: docs
weight: 30
url: /ar/net/aspose.svg.datatypes/svglength/valueasstring/
---
## SVGLength.ValueAsString property

القيمة كسلسلة نصية، بالوحدات التي يحددها unitType. سيؤدي ضبط هذه السمة إلى تحديث value و valueInSpecifiedUnits و unitType تلقائيًا لتعكس هذا الإعداد.

```csharp
public string ValueAsString { get; set; }
```

### Property Value

القيمة كسلسلة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) يُرفع إذا لم يتمكن تحليل السلسلة المعينة كطول صالح. |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) يُرفع عندما يتطابق الطول مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
