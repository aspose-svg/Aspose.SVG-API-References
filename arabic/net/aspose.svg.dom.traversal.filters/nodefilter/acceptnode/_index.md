---
title: "NodeFilter.AcceptNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة NodeFilter AcceptNode. اختبار ما إذا كانت عقدة محددة مرئية في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. ومع ذلك يمكنك القيام بذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك الخاص."
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

اختبر ما إذا كان العقد المحدد مرئيًا في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. (مع أنه يمكنك فعل ذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك.)

```csharp
public abstract short AcceptNode(Node n)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| n | Node | العقدة للتحقق مما إذا كانت تجتاز الفلتر أم لا. |

### قيمة الإرجاع

ثابت لتحديد ما إذا كان العقد مقبولًا أو مرفوضًا أو تم تخطيه، كما هو معرف أعلاه.

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* class [NodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../../)
