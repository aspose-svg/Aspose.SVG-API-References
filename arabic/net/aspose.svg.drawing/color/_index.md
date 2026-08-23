---
title: "فئة اللون"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Drawing.Color. تتيح لك فئة اللون تحديد الألوان كقيم Red-Green-Blue RGB، قيم Hue-Saturation-Luminosity HSL، قيم Hue-Saturation-Value HSV، قيم Hue-Whiteness-Blackness HWB، قيم lightness-A-B LAB، قيم Luminance-Chroma-Hue LCH، قيم Cyan-Magenta-Yellow-Key CMYK، قيم Natural colors NCOL أو باستخدام اسم اللون. كما يتوفر قناة Alpha للإشارة إلى الشفافية"
type: docs
weight: 3390
url: /ar/net/aspose.svg.drawing/color/
---
## Color class

تتيح لك فئة Color تحديد الألوان كقيم الأحمر-الأخضر-الأزرق (RGB)، أو قيم الصبغة-التشبع-الإضاءة (HSL)، أو قيم الصبغة-التشبع-القيمة (HSV)، أو قيم الصبغة-البياض-السواد (HWB)، أو قيم الإضاءة-A-B (LAB)، أو قيم الإضاءة-اللون-الكروم (LCH)، أو قيم السيان-ماجنتا-أصفر-المفتاح (CMYK)، أو قيم الألوان الطبيعية (NCOL)، أو باستخدام اسم اللون. كما يتوفر قناة ألفا لتحديد الشفافية.

```csharp
public class Color
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [Color](color/#constructor)() | ينشئ مثيلًا جديدًا لفئة `Color`. بشكل افتراضي يكون اللون أسود. |
| [Color](color/#constructor_1)(*byte, byte, byte*) | ينشئ مثيلًا جديدًا لفئة `Color`. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| [Color](color/#constructor_5)(*float, float, float*) | ينشئ مثيلًا جديدًا لفئة `Color`. يجب أن تكون جميع مكونات اللون في النطاق 0-1. |
| [Color](color/#constructor_3)(*int, int, int*) | ينشئ مثيلًا جديدًا لفئة `Color`. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | ينشئ مثيلًا جديدًا لفئة `Color`. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| [Color](color/#constructor_6)(*float, float, float, float*) | ينشئ مثيلًا جديدًا لفئة `Color`. يجب أن تكون جميع مكونات اللون في النطاق 0-1. |
| [Color](color/#constructor_4)(*int, int, int, int*) | ينشئ مثيلًا جديدًا لفئة `Color`. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Alpha](../../aspose.svg.drawing/color/alpha/) { get; } | يمثل المكوّن ألفا للون. |
| [Blue](../../aspose.svg.drawing/color/blue/) { get; } | يمثل المكوّن الأزرق للون. |
| [Green](../../aspose.svg.drawing/color/green/) { get; } | يمثل المكوّن الأخضر للون. |
| [Red](../../aspose.svg.drawing/color/red/) { get; } | يمثل المكوّن الأحمر للون. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromCmyk](../../aspose.svg.drawing/color/fromcmyk/)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للسيان، الماجنتا، الأصفر، المفتاح (الأسود). |
| static [FromCmyka](../../aspose.svg.drawing/color/fromcmyka/)(*float, float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للسيان، الماجنتا، الأصفر، المفتاح (الأسود)، وألفا. |
| static [FromGray](../../aspose.svg.drawing/color/fromgray/)(*float*) | يرجع Color جديد مع القيمة المطلوبة للرمادي. |
| static [FromHsl](../../aspose.svg.drawing/color/fromhsl/)(*float, float, float*) | يرجع Color جديد مع القيم المطلوبة للدرجة، التشبع، التشبع. |
| static [FromHsla](../../aspose.svg.drawing/color/fromhsla/)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للدرجة، التشبع، التشبع، وألفا. |
| static [FromHsv](../../aspose.svg.drawing/color/fromhsv/)(*float, float, float*) | يرجع Color جديد مع القيم المطلوبة للدرجة، التشبع، القيمة. |
| static [FromHsva](../../aspose.svg.drawing/color/fromhsva/)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للدرجة، التشبع، القيمة، وألفا. |
| static [FromHwb](../../aspose.svg.drawing/color/fromhwb/)(*float, float, float*) | يرجع Color جديد مع القيم المطلوبة للدرجة، البياض، السواد. |
| static [FromHwba](../../aspose.svg.drawing/color/fromhwba/)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للدرجة، البياض، السواد. |
| static [FromInt](../../aspose.svg.drawing/color/fromint/)(*int*) | يرجع Color جديد مع القيمة المطلوبة لـ ARGB. |
| static [FromLab](../../aspose.svg.drawing/color/fromlab/)(*float, float, float*) | يرجع Color جديد مع القيم المطلوبة للسطوع، A، B. |
| static [FromLaba](../../aspose.svg.drawing/color/fromlaba/)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للسطوع، A، B، وألفا. |
| static [FromLch](../../aspose.svg.drawing/color/fromlch/)(*float, float, float*) | يرجع Color جديد مع القيم المطلوبة للإضاءة، التشبع اللوني، والدرجة. |
| static [FromLcha](../../aspose.svg.drawing/color/fromlcha/)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للإضاءة، التشبع اللوني، الدرجة، وألفا. |
| static [FromOklab](../../aspose.svg.drawing/color/fromoklab/)(*float, float, float*) | يرجع Color جديد مع القيم المطلوبة للسطوع، A، B لنموذج OKLAB. |
| static [FromOklaba](../../aspose.svg.drawing/color/fromoklaba/)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للسطوع، A، B، وألفا لنموذج OKLAB. |
| static [FromOklch](../../aspose.svg.drawing/color/fromoklch/)(*float, float, float*) | يرجع Color جديد مع القيم المطلوبة للإضاءة، التشبع اللوني، الدرجة لنموذج OKLAB. |
| static [FromOklcha](../../aspose.svg.drawing/color/fromoklcha/)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للإضاءة، التشبع اللوني، الدرجة، وألفا لنموذج OKLAB. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | يرجع Color جديد مع القيم المطلوبة للـ ged، الأخضر، الأزرق. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | يرجع Color جديد مع القيم المطلوبة للـ ged، الأخضر، الأزرق. يجب أن تكون جميع مكونات اللون في النطاق 0-1. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | يرجع Color جديد مع القيم المطلوبة للـ ged، الأخضر، الأزرق. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | يرجع Color جديد مع القيم المطلوبة للـ ged، الأخضر، الأزرق، وألفا. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | يرجع Color جديد مع القيم المطلوبة للـ ged، الأخضر، الأزرق، وألفا. يجب أن تكون جميع مكونات اللون في النطاق 0-1. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | يرجع Color جديد مع القيم المطلوبة للـ ged، الأخضر، الأزرق، وألفا. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromString](../../aspose.svg.drawing/color/fromstring/)(*string*) | يقوم بتحليل السلسلة التي تحتوي على لون CSS ويعيد Color جديد. |
| static [FromUint](../../aspose.svg.drawing/color/fromuint/)(*uint*) | يرجع Color جديد مع القيمة المطلوبة لـ ARGB. |
| [AddLuminosity](../../aspose.svg.drawing/color/addluminosity/)(*float*) | ينشئ نسخة من Color مع مجموع إضائته وقيمة الدلتا. |
| [Convert](../../aspose.svg.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | يرجع مكونات اللون بالتنسيق الخاص بنموذج اللون المحدد. |
| override [Equals](../../aspose.svg.drawing/color/equals/)(*object*) | يحدد ما إذا كان `Color` المحدد يساوي هذه الحالة. |
| [GetComplementary](../../aspose.svg.drawing/color/getcomplementary/)() | يعيد لونًا جديدًا يقع على الجانب المقابل لعجلة الألوان من اللون الأصلي. |
| override [GetHashCode](../../aspose.svg.drawing/color/gethashcode/)() | يعيد رمز تجزئة. |
| [GetHue](../../aspose.svg.drawing/color/gethue/)() | يعيد قيمة Hue للون. |
| [GetLuminosity](../../aspose.svg.drawing/color/getluminosity/)() | يعيد قيمة luminosity للون. |
| [GetSaturation](../../aspose.svg.drawing/color/getsaturation/)() | يعيد قيمة saturation للون. |
| [ToInt](../../aspose.svg.drawing/color/toint/)() | يقوم بترميز مكونات ARGB للون إلى int. |
| [ToName](../../aspose.svg.drawing/color/toname/)() | يعيد اسم اللون إذا كان يطابق لونًا في قائمة ألوان CSS المسماة، أو سلسلة فارغة. |
| [ToNaturalColorString](../../aspose.svg.drawing/color/tonaturalcolorstring/)(*int*) | يعيد لونًا محددًا باستخدام Natural colors (NCol) عبر حرف اللون مع رقم لتحديد المسافة (بالنسبة المئوية) من اللون. |
| [ToRgbaHexString](../../aspose.svg.drawing/color/torgbahexstring/)() | يعيد لونًا سداسيًا عشريًا يُحدد بـ: #RRGGBBAA. |
| [ToRgbaString](../../aspose.svg.drawing/color/torgbastring/)() | يعيد سلسلة تحتوي على لون RGBA المحدد بـ: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.svg.drawing/color/torgbhexstring/)() | يعيد لونًا سداسيًا عشريًا يُحدد بـ: #RRGGBB. |
| [ToRgbString](../../aspose.svg.drawing/color/torgbstring/)() | يعيد سلسلة تحتوي على لون RGB المحدد بـ: rgb(R, G, B). |
| override [ToString](../../aspose.svg.drawing/color/tostring/)() | يعيد سلسلة تتكون من قيم مكونات RGBA. |
| [ToUint](../../aspose.svg.drawing/color/touint/)() | يقوم بترميز مكونات ARGB للون إلى unsigned int. |
| [WithAlpha](../../aspose.svg.drawing/color/withalpha/)(*float*) | ينشئ نسخة من اللون مع مكون ألفا المحدد. |
| [WithHue](../../aspose.svg.drawing/color/withhue/)(*float*) | ينشئ نسخة من اللون مع Hue المحدد. |
| [WithLuminosity](../../aspose.svg.drawing/color/withluminosity/)(*float*) | ينشئ نسخة من اللون مع luminosity المحدد. |
| [WithSaturation](../../aspose.svg.drawing/color/withsaturation/)(*float*) | ينشئ نسخة من اللون مع saturation المحدد. |

### انظر أيضًا

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
