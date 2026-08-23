---
title: "فئة SVGLength"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.DataTypes.SVGLength. تتطابق واجهة SVGLength مع نوع البيانات الأساسي للطول. يمكن تعيين كائن SVGLength على أنه للقراءة فقط، مما يعني أن محاولات تعديل الكائن ستؤدي إلى استثناء يُرمى كما هو موضح أدناه"
type: docs
weight: 2210
url: /ar/net/aspose.svg.datatypes/svglength/
---
## SVGLength class

واجهة SVGLength تتطابق مع نوع البيانات الأساسي length. يمكن تعيين كائن SVGLength كقراءة فقط، مما يعني أن محاولات تعديل الكائن ستؤدي إلى رمي استثناء، كما هو موضح أدناه.

```csharp
public class SVGLength : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svglength/unittype/) { get; } | نوع القيمة كما هو محدد بأحد الثوابت SVG_LENGTHTYPE_* المعرفة في هذه الواجهة. |
| [Value](../../aspose.svg.datatypes/svglength/value/) { get; set; } | القيمة كقيمة نقطية عائمة، بوحدات المستخدم. سيؤدي ضبط هذه السمة إلى تحديث valueInSpecifiedUnits و valueAsString تلقائيًا لتعكس هذا الإعداد. |
| [ValueAsString](../../aspose.svg.datatypes/svglength/valueasstring/) { get; set; } | القيمة كسلسلة نصية، بالوحدات التي يحددها unitType. سيؤدي ضبط هذه السمة إلى تحديث value و valueInSpecifiedUnits و unitType تلقائيًا لتعكس هذا الإعداد. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | القيمة كقيمة نقطية عائمة، بالوحدات التي يحددها unitType. سيؤدي ضبط هذه السمة إلى تحديث value و valueAsString تلقائيًا لتعكس هذا الإعداد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svglength/converttospecifiedunits/)(*ushort*) | حافظ على نفس القيمة المخزنة الأساسية، ولكن أعد تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجة لهذه الطريقة. على سبيل المثال، إذا كانت القيمة الأصلية "0.5cm" وتم استدعاء الطريقة للتحويل إلى مليمترات، فإن unitType سيتغير إلى SVG_LENGTHTYPE_MM، و valueInSpecifiedUnits سيتغير إلى القيمة العددية 5، و valueAsString سيتغير إلى "5mm". |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و- اختياريًا - المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svglength/newvaluespecifiedunits/)(*ushort, float*) | أعد ضبط القيمة كرقم مع unitType المرتبط، وبالتالي استبدال القيم لجميع السمات على الكائن. |
| override [ToString](../../aspose.svg.datatypes/svglength/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.svg.datatypes/svglength/svg_lengthtype_cm/) | تم تحديد قيمة باستخدام وحدات cm المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.svg.datatypes/svglength/svg_lengthtype_ems/) | تم تحديد قيمة باستخدام وحدات em المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.svg.datatypes/svglength/svg_lengthtype_exs/) | تم تحديد قيمة باستخدام وحدات ex المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.svg.datatypes/svglength/svg_lengthtype_in/) | تم تحديد قيمة باستخدام وحدات in المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.svg.datatypes/svglength/svg_lengthtype_mm/) | تم تحديد قيمة باستخدام وحدات mm المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.svg.datatypes/svglength/svg_lengthtype_number/) | لم يتم توفير نوع وحدة (أي تم تحديد قيمة بدون وحدة)، مما يشير إلى قيمة بوحدات المستخدم. |
| const [SVG_LENGTHTYPE_PC](../../aspose.svg.datatypes/svglength/svg_lengthtype_pc/) | تم تحديد قيمة باستخدام وحدات pc المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.svg.datatypes/svglength/svg_lengthtype_percentage/) | تم تحديد قيمة كنسبة مئوية. |
| const [SVG_LENGTHTYPE_PT](../../aspose.svg.datatypes/svglength/svg_lengthtype_pt/) | تم تحديد قيمة باستخدام وحدات pt المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.svg.datatypes/svglength/svg_lengthtype_px/) | تم تحديد قيمة باستخدام وحدات px المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.svg.datatypes/svglength/svg_lengthtype_unknown/) | نوع الوحدة ليس أحد الأنواع المعرفة مسبقًا. من غير الصالح محاولة تعريف قيمة جديدة من هذا النوع أو محاولة تحويل قيمة موجودة إلى هذا النوع. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
