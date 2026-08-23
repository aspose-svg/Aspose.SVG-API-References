---
title: "فئة DOMException"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.DOMException. تمثل واجهة DOMException حدثًا غير طبيعي يُسمى استثناءً يحدث نتيجة استدعاء طريقة أو الوصول إلى خاصية من واجهة برمجة تطبيقات الويب. هذا هو الأسلوب الأساسي لوصف حالات الخطأ في واجهات برمجة تطبيقات الويب."
type: docs
weight: 2790
url: /ar/net/aspose.svg.dom/domexception/
---
## DOMException class

واجهة DOMException تمثل حدثًا غير طبيعي (يسمى استثناء) يحدث نتيجة استدعاء طريقة أو الوصول إلى خاصية في واجهة برمجة تطبيقات الويب. هذا هو الأساس في وصف حالات الخطأ في واجهات برمجة تطبيقات الويب.

```csharp
public class DOMException : PlatformException
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [DOMException](domexception/#constructor)(*string*) | يُنشئ مثيلًا جديدًا من الفئة `DOMException`. |
| [DOMException](domexception/#constructor_1)(*string, string*) | يُنشئ مثيلًا جديدًا من الفئة `DOMException`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | يعيد قيمة تحتوي على أحد ثوابت رمز الخطأ، أو 0 إذا لم يتطابق أي منها. يُستخدم هذا الحقل لأسباب تاريخية. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | يعيد سلسلة تمثل رسالة أو وصفًا مرتبطًا باسم الخطأ المعطى. |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | يعيد سلسلة تحتوي على أحد السلاسل المرتبطة باسم الخطأ. |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | تم إلغاء العملية. |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | لا يمكن استنساخ الكائن. |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | إذا لم يتناسب النطاق المحدد من النص مع DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | إذا تم إدراج أي Node في مكان لا ينتمي إليه. |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | إذا كان الفهرس أو الحجم سالبًا، أو أكبر من القيمة المسموح بها. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | إذا تم محاولة إضافة سمة مستخدمة بالفعل في مكان آخر. |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | إذا لم يكن المعامل أو العملية مدعومًا من قبل الكائن الأساسي. |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | إذا تم تحديد حرف غير صالح أو غير قانوني، مثل في اسم XML. |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | التعبير يحتوي على خطأ في الصياغة أو ليس تعبيرًا قانونيًا وفقًا لقواعد XPathEvaluator المحدد أو يحتوي على وظائف امتداد متخصصة أو متغيرات غير مدعومة من قبل هذا التنفيذ. |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | إذا تم محاولة تعديل نوع الكائن الأساسي. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | العقدة المقدمة غير صحيحة أو لها سلف غير صحيح لهذه العملية. |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | إذا تم محاولة استخدام كائن غير قابل للاستخدام أو لم يعد قابلًا للاستخدام. |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | إذا تم محاولة إنشاء أو تغيير كائن بطريقة غير صحيحة فيما يتعلق بأسماء النطاق. |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | حدث خطأ في الشبكة. |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | إذا تم محاولة الإشارة إلى Node في سياق لا وجود له. |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | إذا لم يدعم التنفيذ نوع الكائن أو العملية المطلوبة. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | إذا تم تحديد بيانات لعقدة لا تدعم البيانات. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | إذا تم محاولة تعديل كائن حيث لا يُسمح بالتعديلات. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | تم تجاوز الحصة. |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | العملية غير آمنة. |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | إذا تم تحديد سلسلة غير صالحة أو غير قانونية. |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | انتهت مهلة العملية. |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | لا يمكن تحويل التعبير لإرجاع النوع المحدد. |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | إذا كان نوع الكائن غير متوافق مع النوع المتوقع للمعامل المرتبط بالكائن. |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | عنوان URL المقدم لا يطابق عنوان URL آخر. |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | إذا كان استدعاء طريقة مثل insertBefore أو removeChild سيجعل العقدة غير صالحة بالنسبة إلى الصلاحية الجزئية، فسيتم رفع هذا الاستثناء ولن تُنفذ العملية. يُستخدم هذا الرمز في [DOM Level 3 Validation]. راجع هذه المواصفة لمزيد من المعلومات. |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | إذا تم استخدام عقدة في مستند مختلف عن المستند الذي أنشأها (الذي لا يدعمها). |

### انظر أيضًا

* class [PlatformException](../../aspose.svg/platformexception/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
