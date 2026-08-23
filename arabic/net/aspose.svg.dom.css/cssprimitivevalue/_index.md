---
title: "فئة CSSPrimitiveValue"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.Css.CSSPrimitiveValue. تمثل واجهة CSSPrimitiveValue قيمة CSS واحدة. يمكن استخدام هذه الواجهة لتحديد قيمة خاصية نمط معينة مُعينة حاليًا في كتلة أو لتعيين خاصية نمط معينة صراحةً داخل الكتلة. قد يتم الحصول على مثال من هذه الواجهة عبر طريقة getPropertyCSSValue في واجهة CSSStyleDeclaration. كائن CSSPrimitiveValue يظهر فقط في سياق خاصية CSS."
type: docs
weight: 2480
url: /ar/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

تمثل واجهة CSSPrimitiveValue قيمة CSS واحدة. يمكن استخدام هذه الواجهة لتحديد قيمة خاصية نمط معينة تم تعيينها حاليًا في كتلة أو لتعيين خاصية نمط معينة صراحةً داخل الكتلة. يمكن الحصول على مثال من هذه الواجهة عبر طريقة getPropertyCSSValue في واجهة CSSStyleDeclaration. لا يظهر كائن CSSPrimitiveValue إلا في سياق خاصية CSS.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | خاصية CSSText في واجهة [`CSSValue`](../cssvalue/) تمثل القيمة الحالية للخاصية المحسوبة في CSS. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | رمز يحدد نوع القيمة. |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | نوع القيمة كما هو معرف بالثوابت المحددة أعلاه. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | يحدد ما إذا كان الكائن المحدد يساوي هذه النسخة. |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | تُستخدم هذه الطريقة للحصول على قيمة Counter. إذا لم تحتوي قيمة CSS هذه على قيمة عداد، يتم رفع استثناء DOMException. يمكن تعديل الخاصية النمطية المقابلة باستخدام واجهة Counter. |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(*ushort*) | تُستخدم هذه الطريقة للحصول على قيمة عائمة (float) بوحدة محددة. إذا لم تحتوي قيمة CSS هذه على قيمة عائمة أو لا يمكن تحويلها إلى الوحدة المحددة، يتم رفع استثناء DOMException. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | يرجع رمز تجزئة (hash code) لهذه الحالة. |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(*ushort*) | تُستخدم هذه الطريقة للحصول على قيمة صحيحة (int) بوحدة محددة. إذا لم تحتوي قيمة CSS هذه على قيمة صحيحة أو لا يمكن تحويلها إلى الوحدة المحددة، يتم رفع استثناء DOMException. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | تُستخدم هذه الطريقة للحصول على قيمة Rect. إذا لم تحتوي قيمة CSS هذه على قيمة rect، يتم رفع استثناء DOMException. يمكن تعديل الخاصية النمطية المقابلة باستخدام واجهة Rect. |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | تُستخدم هذه الطريقة للحصول على لون RGB. إذا لم تحتوي قيمة CSS هذه على قيمة لون RGB، يتم رفع استثناء DOMException. يمكن تعديل الخاصية النمطية المقابلة باستخدام واجهة RGBColor. |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | تُستخدم هذه الطريقة للحصول على القيمة النصية. إذا لم تحتوي قيمة CSS على قيمة نصية، يتم رفع استثناء DOMException. |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(*ushort, float*) | طريقة لتعيين القيمة العائمة (float) بوحدة محددة. إذا لم تستطع الخاصية المرتبطة بهذه القيمة قبول الوحدة المحددة أو القيمة العائمة، ستبقى القيمة دون تغيير وسيتم رفع استثناء DOMException. |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(*ushort, int*) | طريقة لتعيين قيمة int بوحدة محددة. إذا كانت الخاصية المرتبطة بهذه القيمة لا يمكنها قبول الوحدة المحددة أو قيمة int، فستظل القيمة دون تغيير وسيتم رفع استثناء DOMException. |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(*ushort, string*) | طريقة لتعيين قيمة السلسلة بوحدة محددة. إذا كانت الخاصية المرتبطة بهذه القيمة لا يمكنها قبول الوحدة المحددة أو قيمة السلسلة، فستظل القيمة دون تغيير وسيتم رفع استثناء DOMException. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | القيمة هي دالة سمة. يمكن الحصول على القيمة باستخدام طريقة getStringValue. |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | القيمة هي طول (ch). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | القيمة هي طول (cm). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | القيمة هي دالة عداد أو عدادات. يمكن الحصول على القيمة باستخدام طريقة GetCounterValue. |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | القيمة هي زاوية (deg). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | القيمة هي رقم بأبعاد غير معروفة. يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | القيمة هي نقاط لكل سنتيمتر (dpcm). |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | القيمة هي نقاط لكل بوصة (dpi). |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | القيمة هي نقاط لكل وحدة ‘px’ (dppx). |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | القيمة هي طول (ems). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | القيمة هي طول (exs). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_FR](../../aspose.svg.dom.css/cssprimitivevalue/css_fr/) | الطول المرن أو flex هو بُعد بوحدة fr، والتي تمثل جزءًا من المساحة المتبقية في حاوية الشبكة. |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | القيمة هي زاوية (grad). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | القيمة هي تردد (Hz). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | القيمة هي معرف. يمكن الحصول على القيمة باستخدام طريقة getStringValue. |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | القيمة هي طول (in). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | القيمة هي تردد (kHz). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | القيمة هي طول (mm). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | القيمة هي زمن (ms). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | القيمة هي رقم بسيط. يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | القيمة هي طول (pc). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | القيمة هي نسبة مئوية. يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | القيمة هي طول (pt). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | القيمة هي طول (px). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | القيمة هي زاوية (rad). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | القيمة هي دالة rect. يمكن الحصول على القيمة باستخدام طريقة GetRectValue. |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | القيمة هي طول (rem). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | القيمة هي لون RGB. يمكن الحصول على القيمة باستخدام طريقة GetRGBColorValue. |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | القيمة هي زمن (s). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | القيمة هي STRING. يمكن الحصول على القيمة باستخدام طريقة getStringValue. |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | القيمة ليست قيمة CSS2 معروفة. لا يمكن الحصول على القيمة إلا باستخدام السمة cssText. |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | القيمة هي URI. يمكن الحصول على القيمة باستخدام طريقة getStringValue. |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | القيمة هي نسبة مئوية من ارتفاع العرض الكامل. |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | القيمة هي نسبة مئوية من عرض أو ارتفاع العرض، أيهما أكبر. |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | القيمة هي نسبة مئوية من عرض أو ارتفاع العرض، أيهما أصغر. |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | القيمة هي نسبة مئوية من عرض العرض الكامل. |
| const [CSS_X](../../aspose.svg.dom.css/cssprimitivevalue/css_x/) | القيمة هي نقاط لكل وحدة ‘px’ (x). |

### انظر أيضًا

* class [CSSValue](../cssvalue/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
