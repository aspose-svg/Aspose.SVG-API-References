---
title: "INodeIterator.NextNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة INodeIterator NextNode. تُرجع العقدة التالية في المجموعة وتُقدِّم موضع المُكرِّر في المجموعة. بعد إنشاء NodeIterator، تُعيد الاستدعاءة الأولى لـ nextNode العقدة الأولى في المجموعة."
type: docs
weight: 40
url: /ar/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

يعيد العقدة التالية في المجموعة ويُحسّن موضع المتتبع في المجموعة. بعد إنشاء NodeIterator، تُعيد الاستدعاءة الأولى إلى nextNode() العقدة الأولى في المجموعة.

```csharp
public Node NextNode()
```

### قيمة الإرجاع

العقدة التالية في المجموعة التي يتم التنقل فيها، أو null إذا لم يعد هناك أي أعضاء في تلك المجموعة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: يُرفع إذا تم استدعاء هذه الطريقة بعد استدعاء طريقة detach. |

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
