---
title: "فئة CSSValueList"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Css.CSSValueList class. توفر واجهة CSSValueList تجريدًا لمجموعة مرتبة من قيم CSS."
type: docs
weight: 2500
url: /ar/net/aspose.svg.dom.css/cssvaluelist/
---
## CSSValueList class

توفر واجهة CSSValueList تجريد مجموعة مرتبة من قيم CSS.

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | يُنشئ مثيلًا جديدًا من الفئة `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | يُنشئ مثيلًا جديدًا من الفئة `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | يُنشئ مثيلًا جديدًا من الفئة `CSSValueList`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CSSText](../../aspose.svg.dom.css/cssvaluelist/csstext/) { get; set; } | خاصية CSSText في واجهة [`CSSValue`](../cssvalue/) تمثل القيمة الحالية للخاصية المحسوبة في CSS. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | رمز يحدد نوع القيمة. |
| [Item](../../aspose.svg.dom.css/cssvaluelist/item/) { get; } | يحصل على [`CSSValue`](../cssvalue/) عند الفهرس المحدد. |
| [Length](../../aspose.svg.dom.css/cssvaluelist/length/) { get; } | خاصية الطول (read-only) في واجهة CSSValueList تمثل عدد عناصر CSSValue في القائمة. نطاق القيم الصالحة للفهارس هو من 0 إلى length-1 شاملًا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | يحدد ما إذا كان الكائن المحدد يساوي هذه النسخة. |
| [GetEnumerator](../../aspose.svg.dom.css/cssvaluelist/getenumerator/)() | يرجع كائن enumerator يتنقل عبر المجموعة. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | يرجع رمز تجزئة (hash code) لهذه الحالة. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvaluelist/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |

### انظر أيضًا

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
