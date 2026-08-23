---
title: "SVGAngle.ValueAsString"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "خاصية SVGAngle ValueAsString. قيمة الزاوية كسلسلة في الوحدات التي يعبر عنها unitType. ضبط هذا السمة سيؤدي إلى تحديث value valueInSpecifiedUnits و unitType تلقائيًا لتعكس هذا الإعداد."
type: docs
weight: 30
url: /ar/net/aspose.svg.datatypes/svgangle/valueasstring/
---
## SVGAngle.ValueAsString property

قيمة الزاوية كسلسلة نصية، بالوحدات التي يحددها unitType. سيؤدي ضبط هذا السمة إلى تحديث value و valueInSpecifiedUnits و unitType تلقائيًا لتعكس هذا الإعداد.

```csharp
public string ValueAsString { get; set; }
```

### Property Value

القيمة كسلسلة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) يُرفع إذا تعذر تحليل السلسلة المعينة كزاوية صالحة. |
| [DOMException](../../../aspose.svg.dom/domexception/) | الكود [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) يُرفع عندما تتطابق الزاوية مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
