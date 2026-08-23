---
title: "واجهة IMediaList"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.Css.IMediaList. توفر واجهة MediaList تجريدًا لمجموعة مرتبة من الوسائط دون تحديد أو تقييد كيفية تنفيذ هذه المجموعة. القائمة الفارغة هي نفسها القائمة التي تحتوي على جميع الوسائط."
type: docs
weight: 2730
url: /ar/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

توفر واجهة MediaList تجريدًا لمجموعة مرتبة من الوسائط، دون تعريف أو تقييد طريقة تنفيذ هذه المجموعة. القائمة الفارغة هي نفسها القائمة التي تحتوي على الوسيط "all".

```csharp
public interface IMediaList : IEnumerable<string>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | يرجع العنصر في الموضع index في القائمة. إذا كان index أكبر من أو يساوي عدد الوسائط في القائمة، فإنها تُعيد null. فهرس الوسائط. |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | عدد الوسائط في القائمة. النطاق الصالح للوسائط هو من 0 إلى length-1 شاملًا. |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | التمثيل النصي القابل للتحليل لقائمة الوسائط. هذه قائمة وسائط مفصولة بفواصل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(*string*) | يضيف الوسيط newMedium إلى نهاية القائمة. إذا كان newMedium مستخدمًا بالفعل، يتم إزالته أولاً. |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(*string*) | يحذف الوسيط المشار إليه بـ oldMedium من القائمة. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
