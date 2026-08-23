---
title: "واجهة IDOMImplementation"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.IDOMImplementation. توفر واجهة DOMImplementation عددًا من الطرق لتنفيذ عمليات لا تعتمد على أي نسخة معينة من نموذج كائن المستند."
type: docs
weight: 3040
url: /ar/net/aspose.svg.dom/idomimplementation/
---
## IDOMImplementation interface

توفر واجهة DOMImplementation عددًا من الطرق لتنفيذ عمليات مستقلة عن أي نسخة معينة من نموذج كائن المستند.

```csharp
public interface IDOMImplementation
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateDocument](../../aspose.svg.dom/idomimplementation/createdocument/)(*string, string, [DocumentType](../documenttype/)*) | ينشئ كائن DOM Document من النوع المحدد مع عنصر المستند الخاص به. |
| [CreateDocumentType](../../aspose.svg.dom/idomimplementation/createdocumenttype/)(*string, string, string*) | ينشئ عقدة DocumentType فارغة. لا تتوفر إعلانات الكيانات والرموز. لا تحدث توسيعات مرجع الكيان ولا إضافات السمات الافتراضية. |
| [CreateHTMLDocument](../../aspose.svg.dom/idomimplementation/createhtmldocument/)(*string*) | يعيد مستندًا، مع شجرة أساسية تم إنشاؤها مسبقًا بما في ذلك عنصر عنوان، ما لم يتم حذف معامل العنوان. |
| [HasFeature](../../aspose.svg.dom/idomimplementation/hasfeature/)() | اختبر ما إذا كان تنفيذ DOM يدعم ميزة وإصدار محددين، كما هو موضح في ميزات DOM. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
