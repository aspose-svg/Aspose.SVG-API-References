---
title: "فئة DOMTokenList"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Collections.DOMTokenList. تمثل فئة DOMTokenList مجموعة من الرموز المفصولة بمسافات. يتم فهرستها بدءًا من 0 كما هو الحال مع كائنات مصفوفة JavaScript. DOMTokenList حساسة دائمًا لحالة الأحرف."
type: docs
weight: 2000
url: /ar/net/aspose.svg.collections/domtokenlist/
---
## DOMTokenList class

تمثل فئة DOMTokenList مجموعة من الرموز المفصولة بمسافات. يتم فهرستها بدءًا من 0 كما هو الحال مع كائنات مصفوفة JavaScript. DOMTokenList دائمًا حساسة لحالة الأحرف.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Item](../../aspose.svg.collections/domtokenlist/item/) { get; } | يرجع العنصر في القائمة حسب فهرسه، أو null إذا كان الفهرس أكبر من أو يساوي طول القائمة. |
| [Length](../../aspose.svg.collections/domtokenlist/length/) { get; } | يرجع قيمة ulong تمثل عدد الرموز المخزنة في هذه القائمة. |
| [Value](../../aspose.svg.collections/domtokenlist/value/) { get; set; } | يحصل أو يضبط قيمة السمة المقابلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.svg.collections/domtokenlist/add/)(*params string[]*) | يضيف الرمز (الرموز) المحدد إلى القائمة. |
| [Contains](../../aspose.svg.collections/domtokenlist/contains/)(*string*) | يرجع true إذا كانت القائمة تحتوي على الرمز المعطى، وإلا false. |
| [GetEnumerator](../../aspose.svg.collections/domtokenlist/getenumerator/)() | يرجع كائن enumerator يتنقل عبر المجموعة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [Remove](../../aspose.svg.collections/domtokenlist/remove/)(*params string[]*) | يزيل الرمز (الرموز) المحدد من القائمة. |
| [Replace](../../aspose.svg.collections/domtokenlist/replace/)(*string, string*) | يستبدل رمزًا موجودًا برمز جديد. لا يفعل شيئًا إذا لم يكن الرمز الأول موجودًا. |
| [Supports](../../aspose.svg.collections/domtokenlist/supports/)(*string*) | يرجع true إذا كان الرمز المعطى موجودًا في الرموز المدعومة للخاصية المرتبطة. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle)(*string*) | يزيل الرمز من القائمة إذا كان موجودًا، أو يضيفه إلى القائمة إذا لم يكن موجودًا. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle_1)(*string, bool*) | يزيل الرمز من القائمة إذا كان موجودًا، أو يضيفه إلى القائمة إذا لم يكن موجودًا. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
