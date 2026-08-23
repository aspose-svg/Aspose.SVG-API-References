---
title: "SVGAngle فئة"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.DataTypes.SVGAngle فئة. واجهة SVGAngle تتوافق مع نوع البيانات الأساسي angle"
type: docs
weight: 2070
url: /ar/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

واجهة SVGAngle تتطابق مع نوع البيانات الأساسي angle.

```csharp
public class SVGAngle : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | نوع القيمة كما هو محدد بأحد الثوابت SVG_ANGLETYPE_* المعرفة على هذه الواجهة. |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | قيمة الزاوية كقيمة نقطية عائمة، بالدرجات. سيؤدي ضبط هذا السمة إلى تحديث valueInSpecifiedUnits و valueAsString تلقائيًا لتعكس هذا الإعداد. |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | قيمة الزاوية كسلسلة نصية، بالوحدات التي يحددها unitType. سيؤدي ضبط هذا السمة إلى تحديث value و valueInSpecifiedUnits و unitType تلقائيًا لتعكس هذا الإعداد. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | قيمة الزاوية كقيمة نقطية عائمة، بالوحدات التي يحددها unitType. سيؤدي ضبط هذا السمة إلى تحديث value و valueAsString تلقائيًا لتعكس هذا الإعداد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(*ushort*) | حافظ على القيمة المخزنة الأساسية نفسها، ولكن أعد ضبط معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجةً لهذه الطريقة. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و- اختياريًا - المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(*ushort, float*) | أعد ضبط القيمة كرقم مع unitType المرتبط، وبالتالي استبدال القيم لجميع السمات على الكائن. |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | تم تعيين نوع الوحدة صراحةً إلى الدرجات. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | نوع الوحدة هو الراديان. |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | نوع الوحدة هو الراديان. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | نوع الوحدة ليس أحد الأنواع المعرفة مسبقًا. من غير الصالح محاولة تعريف قيمة جديدة من هذا النوع أو محاولة تحويل قيمة موجودة إلى هذا النوع. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | لم يتم توفير نوع وحدة (أي تم تحديد قيمة بدون وحدة). بالنسبة للزوايا، تُعامل القيمة بدون وحدة كما لو تم تحديد الدرجات. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
