---
title: "Resource.Embed"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Resource Embed. تقوم بدمج هذا المورد داخل الأصل عن طريق ترميزه كـ Base64. سيتم كتابة نتيجة الترميز إلى OutputUrl"
type: docs
weight: 60
url: /ar/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

يقوم بدمج هذا المورد داخل الأصل عن طريق ترميزه كـ Base64. سيتم كتابة نتيجة الترميز إلى [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| context | ResourceHandlingContext | سياق معالجة المورد. |

### قيمة الإرجاع

هذا المورد لتتمكن من سلاسل الاستدعاءات.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يتم رفع الاستثناء إذا لم يكن هناك [`ParentResource`](../../resourcehandlingcontext/parentresource/) لأنه لا يوجد مكان لدمج النتيجة. |

### انظر أيضًا

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
