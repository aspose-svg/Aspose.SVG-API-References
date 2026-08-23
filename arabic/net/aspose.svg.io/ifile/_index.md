---
title: "الواجهة IFile"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الواجهة Aspose.Svg.IO.IFile. كائن File هو كائن Blob يحتوي على سمة name التي هي سلسلة نصية يمكن إنشاؤه داخل تطبيق الويب عبر مُنشئ أو يكون إشارة إلى تسلسل بايتات من ملف في نظام ملفات نظام التشغيل الأساسي"
type: docs
weight: 4050
url: /ar/net/aspose.svg.io/ifile/
---
## IFile interface

كائن File هو كائن Blob مع سمة name، وهي سلسلة؛ يمكن إنشاؤه داخل تطبيق الويب عبر مُنشئ، أو يكون إشارة إلى تسلسل بايتات من ملف في نظام الملفات الأساسي (OS).

```csharp
public interface IFile : IBlob
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [LastModified](../../aspose.svg.io/ifile/lastmodified/) { get; } | تاريخ آخر تعديل للملف. عند الحصول، إذا كان بإمكان وكلاء المستخدم توفير هذه المعلومة، يجب إرجاع قيمة من نوع long long تمثل وقت آخر تعديل للملف كعدد من الملليثانية منذ حقبة يونكس. |
| [Name](../../aspose.svg.io/ifile/name/) { get; } | اسم الملف. عند الحصول، يجب إرجاع اسم الملف كسلسلة نصية. |

### انظر أيضًا

* interface [IBlob](../iblob/)
* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)
