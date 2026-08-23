---
title: "فئة Location"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Window.Location. توفر كائنات Location تمثيلًا لعنوان المستند النشط في سياق تصفح مستنداتهم وتسمح بتغيير الإدخال الحالي في سجل جلسة تصفح السياق عن طريق إضافة أو استبدال الإدخالات في كائن السجل."
type: docs
weight: 5950
url: /ar/net/aspose.svg.window/location/
---
## Location class

توفر كائنات Location تمثيلاً لعنوان المستند النشط في سياق التصفح الخاص بوثيقتهم، وتسمح بتغيير الإدخال الحالي في سجل جلسة سياق التصفح عن طريق إضافة أو استبدال الإدخالات في كائن السجل.

```csharp
public sealed class Location : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Hash](../../aspose.svg.window/location/hash/) { get; set; } | يرجع الجزء (fragment) من عنوان URL لكائن Location (يتضمن العلامة "#" في البداية إذا لم يكن فارغًا). يمكن تعيينه للتنقل إلى نفس URL مع جزء مُغيّر (يتجاهل العلامة "#" في البداية). |
| [Host](../../aspose.svg.window/location/host/) { get; set; } | يعيد مضيف ومنفذ URL الخاص بكائن Location (إذا كان مختلفًا عن المنفذ الافتراضي للمخطط). يمكن تعيينه للتنقل إلى نفس URL مع تغيير المضيف والمنفذ. |
| [Hostname](../../aspose.svg.window/location/hostname/) { get; set; } | يعيد مضيف URL الخاص بكائن Location. يمكن تعيينه للتنقل إلى نفس URL مع تغيير المضيف. |
| [Href](../../aspose.svg.window/location/href/) { get; set; } | يعيد URL الخاص بكائن Location. يمكن تعيينه للتنقل إلى URL المحدد. |
| [Origin](../../aspose.svg.window/location/origin/) { get; } | يعيد أصل URL الخاص بكائن Location. |
| [Pathname](../../aspose.svg.window/location/pathname/) { get; set; } | يعيد مسار URL الخاص بكائن Location. يمكن تعيينه للتنقل إلى نفس URL مع تغيير المسار. |
| [Port](../../aspose.svg.window/location/port/) { get; set; } | يعيد منفذ URL الخاص بكائن Location. يمكن تعيينه للتنقل إلى نفس URL مع تغيير المنفذ. |
| [Protocol](../../aspose.svg.window/location/protocol/) { get; set; } | يعيد مخطط URL الخاص بكائن Location. يمكن تعيينه للتنقل إلى نفس URL مع تغيير المخطط. |
| [Search](../../aspose.svg.window/location/search/) { get; set; } | يعيد استعلام URL الخاص بكائن Location (يتضمن علامة \"?\" الأولية إذا لم يكن فارغًا). يمكن تعيينه للتنقل إلى نفس URL مع تغيير الاستعلام (يتجاهل علامة \"?\" الأولية). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Assign](../../aspose.svg.window/location/assign/)(*string*) | ينتقل إلى الصفحة المحددة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [Reload](../../aspose.svg.window/location/reload/)() | يعيد تحميل الصفحة الحالية. |
| [Replace](../../aspose.svg.window/location/replace/)(*string*) | يزيل الصفحة الحالية من سجل الجلسة ويتنقل إلى الصفحة المحددة. |
| override [ToString](../../aspose.svg.window/location/tostring/)() | يعيد URL الخاص بكائن Location. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
