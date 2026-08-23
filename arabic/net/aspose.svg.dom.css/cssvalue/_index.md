---
title: "الفئة CSSValue"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الفئة Aspose.Svg.Dom.Css.CSSValue. تمثل قيمة بسيطة أو مركبة. لا يظهر كائن CSSValue إلا في سياق خاصية CSS."
type: docs
weight: 2490
url: /ar/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

يمثل قيمة بسيطة أو مركبة. لا يظهر كائن CSSValue إلا في سياق خاصية CSS.

```csharp
public abstract class CSSValue : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | خاصية CSSText في واجهة `CSSValue` تمثل قيمة خاصية CSS المحسوبة الحالية. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | رمز يحدد نوع القيمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | يحدد ما إذا كان الكائن المحدد يساوي هذه النسخة. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | يرجع رمز تجزئة (hash code) لهذه الحالة. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality/) | ينفّذ العامل ==. |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality/) | ينفّذ العامل !=. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom/) | القيمة هي قيمة مخصصة. |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit/) | القيمة موروثة ويحتوي cssText على "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value/) | القيمة هي قيمة بدائية ويمكن الحصول على نسخة من واجهة CSSPrimitiveValue باستخدام طرق التحويل الخاصة بالربط على هذه النسخة من واجهة CSSValue. |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list/) | القيمة هي قائمة CSSValue ويمكن الحصول على مثيل من واجهة CSSValueList باستخدام طرق التحويل الخاصة بالربط على هذا المثيل من واجهة CSSValue. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
