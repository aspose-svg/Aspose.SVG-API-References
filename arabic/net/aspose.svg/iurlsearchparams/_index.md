---
title: "واجهة IUrlSearchParams"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.IUrlSearchParams. توفر طرقًا للعمل مع سلسلة استعلام عناوين URL"
type: docs
weight: 4140
url: /ar/net/aspose.svg/iurlsearchparams/
---
## IUrlSearchParams interface

يوفر طرقًا للعمل مع سلسلة استعلام URLs.

```csharp
public interface IUrlSearchParams : IEnumerable<string[]>
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Append](../../aspose.svg/iurlsearchparams/append/)(*string, string*) | يضيف زوج اسم-قيمة جديد يكون اسمه `name` وقيمته `value`. |
| [Delete](../../aspose.svg/iurlsearchparams/delete/)(*string*) | يزيل جميع أزواج الاسم-القيمة التي يكون اسمها `name`. |
| [Get](../../aspose.svg/iurlsearchparams/get/)(*string*) | يعيد قيمة أول زوج اسم-قيمة يكون اسمه `name`. |
| [GetAll](../../aspose.svg/iurlsearchparams/getall/)(*string*) | يرجع جميع القيم التي اسمها `name`. |
| [Has](../../aspose.svg/iurlsearchparams/has/)(*string*) | يتحقق مما إذا كان هناك زوج اسم-قيمة اسمه `name` في القائمة. |
| [Set](../../aspose.svg/iurlsearchparams/set/)(*string, string*) | يضبط قيمة أول زوج اسم-قيمة يُعثر عليه إلى القيمة المحددة ويزيل البقية. إذا لم يُعثر على أي أزواج اسم-قيمة بالاسم المحدد، سيتم إضافة زوج جديد إلى القائمة. |
| [Sort](../../aspose.svg/iurlsearchparams/sort/)() | يقوم بترتيب جميع أزواج اسم-قيمة، إن وجدت، حسب أسمائها. |

### انظر أيضًا

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
