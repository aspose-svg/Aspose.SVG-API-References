---
title: "واجهة INodeFilter"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.Traversal.INodeFilter. الفلاتر هي كائنات تعرف كيفية تصفية العقد. إذا تم إعطاء NodeIterator أو TreeWalker كائن NodeFilter، فإنه يطبق الفلتر قبل أن يُعيد العقدة التالية. إذا قال الفلتر بقبول العقدة، تُعيد منطق التجوالها؛ وإلا يبحث التجوال عن العقدة التالية ويتصرف كما لو أن العقدة المرفوضة غير موجودة."
type: docs
weight: 3240
url: /ar/net/aspose.svg.dom.traversal/inodefilter/
---
## INodeFilter interface

الفلاتر هي كائنات تعرف كيفية \"تصفية\" العقد. إذا تم إعطاء NodeIterator أو TreeWalker كائن NodeFilter، فإنه يطبق الفلتر قبل إرجاع العقدة التالية. إذا قال الفلتر بقبول العقدة، تُعيد منطقية التصفحها؛ وإلا، يبحث التصفح عن العقدة التالية ويتظاهر بأن العقدة المرفوضة غير موجودة.

لا يوفر DOM أي فلاتر. NodeFilter هو مجرد واجهة يمكن للمستخدمين تنفيذها لتوفير فلاترهم الخاصة.

لا تحتاج NodeFilters إلى معرفة كيفية الانتقال من عقدة إلى أخرى، ولا تحتاج إلى معرفة أي شيء عن بنية البيانات التي يتم traversed. هذا يجعل كتابة الفلاتر سهلة جدًا، لأن الشيء الوحيد الذي يجب أن تعرفه هو تقييم عقدة واحدة. يمكن استخدام فلتر واحد مع عدد من أنواع traversals المختلفة، مما يشجع على إعادة استخدام الشيفرة.

انظر أيضًا إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeFilter
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AcceptNode](../../aspose.svg.dom.traversal/inodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | اختبر ما إذا كان العقد المحدد مرئيًا في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. (مع أنه يمكنك فعل ذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك.) |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
