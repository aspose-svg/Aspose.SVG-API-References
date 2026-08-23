---
title: "فئة NodeFilter"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.Traversal.Filters.NodeFilter. الفلاتر هي كائنات تعرف كيفية تصفية العقد."
type: docs
weight: 3210
url: /ar/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filters هي كائنات تعرف كيفية "تصفية" العقد.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | اختبر ما إذا كان العقد المحدد مرئيًا في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. (مع أنه يمكنك فعل ذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك.) |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | قبول العقدة. ستُعيد طرق التنقل المعرفة لـ NodeIterator أو TreeWalker هذه العقدة. |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | رفض العقدة. لن تُعيد طرق التنقل المعرفة لـ NodeIterator أو TreeWalker هذه العقدة. بالنسبة لـ TreeWalker، سيتم رفض أبناء هذه العقدة أيضًا. تُعامل NodeIterators هذا كمرادف لـ FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | تجاوز هذه العقدة الوحيدة. لن تُعيد طرق التنقل المعرفة لـ NodeIterator أو TreeWalker هذه العقدة. بالنسبة لكل من NodeIterator و TreeWalker، سيظل يُنظر إلى أبناء هذه العقدة. |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | إظهار جميع العقد. |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | إظهار عقد Attr. هذا ذو معنى فقط عند إنشاء مُكرِّر أو tree-walker بجذر عقدة صفة؛ في هذه الحالة، يعني أن عقدة الصفة ستظهر في الموضع الأول من التكرار أو التجوال. نظرًا لأن الصفات لا تكون أبدًا أبناء لعقد أخرى، فإنها لا تظهر عند التجوال عبر شجرة المستند. |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | إظهار عقد CDATASection. |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | إظهار عقد التعليق. |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | إظهار عقد المستند. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | إظهار عقد DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | إظهار عقد DocumentType. |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | إظهار عقد Element. |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | إظهار عقد Entity. هذا ذو معنى فقط عند إنشاء iterator أو tree-walker مع عقدة Entity كجذر لها؛ في هذه الحالة، يعني ذلك أن عقدة Entity ستظهر في الموضع الأول أثناء التجوال. بما أن الكيانات ليست جزءًا من شجرة المستند، فإنها لا تظهر عند التجول عبر شجرة المستند. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | إظهار عقد EntityReference. |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | إظهار عقد Notation. هذا ذو معنى فقط عند إنشاء iterator أو tree-walker مع عقدة Notation كجذر لها؛ في هذه الحالة، يعني ذلك أن عقدة Notation ستظهر في الموضع الأول أثناء التجوال. بما أن الملاحظات ليست جزءًا من شجرة المستند، فإنها لا تظهر عند التجول عبر شجرة المستند. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | إظهار عقد ProcessingInstruction. |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | إظهار عقد Text. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../)
