---
title: "Resource.Save"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Resource Save. تقوم بحفظ المورد إلى الدفق المقدم."
type: docs
weight: 70
url: /ar/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

يحفظ المورد إلى الدفق المقدم.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | Stream | الدفق الذي سيتم حفظ المورد فيه. |
| context | ResourceHandlingContext | سياق معالجة المورد. |

### قيمة الإرجاع

هذا المورد لتتمكن من سلاسل الاستدعاءات.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يتم رفع الاستثناء إذا كان [`OutputUrl`](../outputurl/) `null`. يجب تحديد [`OutputUrl`](../outputurl/) قبل حفظ المورد لأنه وإلا سيكون من المستحيل تحديد المرجع الصحيح في الموارد التي تشير إلى هذا المورد. |

### انظر أيضًا

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
