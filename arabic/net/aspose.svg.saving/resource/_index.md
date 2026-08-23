---
title: "فئة Resource"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Saving.Resource. تصف هذه الفئة موردًا وتوفر طرقًا لمعالجته"
type: docs
weight: 5710
url: /ar/net/aspose.svg.saving/resource/
---
## Resource class

تصف هذه الفئة موردًا وتوفر طرقًا لمعالجته.

```csharp
public class Resource
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | يرجع !:Html.MimeType لهذا المورد. يمكن أن يكون `null` إذا لم يتم العثور على المورد. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | يعيد سلسلة نصية تحتوي على الإشارة الأصلية إلى هذا المورد. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | يعيد عنوان URL يوضح مكان وجود هذا المورد. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | يحصل أو يضبط عنوان URL الذي يوضح مكان وجود المورد بعد المعالجة. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | يعيد الحالة الحالية للمورد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | يدمج هذا المورد داخل العنصر الأب عن طريق ترميزه كـ Base64. سيتم كتابة نتيجة الترميز إلى [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | يحفظ المورد إلى الدفق المقدم. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | يحدد عنوان URL الجديد الذي يوضح مكان وجود المورد بعد المعالجة. |

### انظر أيضًا

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
