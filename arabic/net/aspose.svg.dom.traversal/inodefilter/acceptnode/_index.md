---
title: "INodeFilter.AcceptNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة INodeFilter AcceptNode. تختبر ما إذا كانت العقدة المحددة مرئية في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator، ولا تُستدعى عادةً مباشرةً من كود المستخدم. ومع ذلك يمكنك استدعاؤها إذا رغبت في استخدام نفس الفلتر لتوجيه منطق تطبيقك الخاص."
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

اختبر ما إذا كان العقد المحدد مرئيًا في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. (مع أنه يمكنك فعل ذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك.)

```csharp
public short AcceptNode(Node n)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| n | Node | العقدة للتحقق مما إذا كانت تجتاز الفلتر أم لا. |

### قيمة الإرجاع

ثابت لتحديد ما إذا كان العقد مقبولًا أو مرفوضًا أو تم تخطيه، كما هو معرف أعلاه.

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
