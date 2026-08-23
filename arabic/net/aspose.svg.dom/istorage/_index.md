---
title: "واجهة IStorage"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.IStorage. توفر هذه الواجهة من واجهة برمجة تطبيقات Web Storage إمكانية الوصول إلى جلسة أو تخزين محلي لنطاق معين. راجع مواصفة Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /ar/net/aspose.svg.dom/istorage/
---
## IStorage interface

توفر هذه الواجهة في Web Storage API إمكانية الوصول إلى جلسة أو تخزين محلي لنطاق معين. راجع مواصفة Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | يعيد عدد أزواج المفتاح/القيمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | يزيل جميع أزواج المفتاح/القيمة، إذا وجدت. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | يعيد القيمة الحالية المرتبطة بالمفتاح المعطى، أو null إذا لم يكن المفتاح موجوداً. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | يعيد اسم المفتاح رقم n، أو null إذا كان n أكبر من أو يساوي عدد أزواج المفتاح/القيمة. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | يزيل زوج المفتاح/القيمة بالمفتاح المعطى، إذا كان هناك زوج مفتاح/قيمة بهذا المفتاح. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | يضبط قيمة الزوج المحدد بالمفتاح إلى value، مع إنشاء زوج مفتاح/قيمة جديد إذا لم يكن هناك أي زوج للمفتاح مسبقاً. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
