---
title: "فئة FileSystemResourceHandler"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler class. هذه الفئة هي تنفيذ لفئة ResourceHandler صُممت لحفظ الموارد إلى نظام الملفات المحلي."
type: docs
weight: 5720
url: /ar/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

هذه الفئة هي تنفيذ لفئة [`ResourceHandler`](../resourcehandler/) صُممت لحفظ الموارد إلى نظام الملفات المحلي.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | ينشئ مثيلًا جديدًا من الفئة `FileSystemResourceHandler`. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | ينشئ مثيلًا جديدًا من الفئة `FileSystemResourceHandler`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | هذه الطريقة مسؤولة عن معالجة المورد. يمكنك من خلالها حفظ [`Resource`](../../aspose.svg.saving/resource/) إلى الدفق أو تضمينه في المورد الأصلي. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | هذه الطريقة مسؤولة عن معالجة مرجع المورد. في هذه الطريقة، يمكنك تحديد الشكل الذي سيظهر به المرجع إلى المورد الذي يتم معالجته. |

### انظر أيضًا

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
