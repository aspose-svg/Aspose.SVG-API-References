---
title: "تعداد PdfPermissions"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "التعداد Aspose.Svg.Rendering.Pdf.Encryption.PdfPermissions. يمثل هذا التعداد أذونات المستخدمين لملف PDF."
type: docs
weight: 5000
url: /ar/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

يمثل هذا التعداد أذونات المستخدم لملف PDF.

```csharp
[Flags]
public enum PdfPermissions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| PrintDocument | `4` | (معالجات الأمان للإصدار 2) طباعة المستند. (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند (قد لا تكون بأعلى مستوى جودة، اعتمادًا على ما إذا تم ضبط PrintingQuality أيضًا). |
| ModifyContent | `8` | تعديل محتويات المستند عبر عمليات غير تلك التي يتحكم فيها ModifyTextAnnotations و FillForm و 11. |
| ExtractContent | `10` | (معالجات الأمان للإصدار 2) نسخ أو استخراج النص والرسومات من المستند بأي طريقة، بما في ذلك استخراج النص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى). (معالجات الأمان للإصدار 3 أو أعلى) نسخ أو استخراج النص والرسومات من المستند عبر عمليات غير تلك التي يتحكم فيها ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | إضافة أو تعديل تعليقات النص، ملء حقول النماذج التفاعلية، وإذا تم ضبط ModifyContent أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع). |
| FillForm | `100` | (معالجات الأمان للإصدار 3 أو أعلى) ملء حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كان ModifyTextAnnotations غير مفعّل. |
| ExtractContentWithDisabilities | `200` | (معالجات الأمان للإصدار 3 أو أعلى) استخراج النص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى). |
| AssembleDocument | `400` | (معالجات الأمان للإصدار 3 أو أعلى) تجميع المستند (إدراج، تدوير، أو حذف صفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كان ModifyContent غير مفعّل. |
| PrintingQuality | `800` | (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من محتوى PDF. عندما يكون هذا البت غير مفعّل (ويكون البت 3 مفعّلاً)، تقتصر الطباعة على تمثيل منخفض المستوى للمظهر، قد يكون بجودة منخفضة. |

### انظر أيضًا

* namespace [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption/)
* assembly [Aspose.SVG](../../)
