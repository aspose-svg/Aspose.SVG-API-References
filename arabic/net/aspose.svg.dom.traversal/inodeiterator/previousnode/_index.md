---
title: "INodeIterator.PreviousNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة INodeIterator PreviousNode. تُرجع العقدة السابقة في المجموعة وتُحرك موضع NodeIterator إلى الخلف في المجموعة"
type: docs
weight: 50
url: /ar/net/aspose.svg.dom.traversal/inodeiterator/previousnode/
---
## INodeIterator.PreviousNode method

يعيد العقدة السابقة في المجموعة وينقل موضع NodeIterator إلى الخلف في المجموعة.

```csharp
public Node PreviousNode()
```

### قيمة الإرجاع

العقدة السابقة في المجموعة التي يتم التنقل فيها، أو null إذا لم يعد هناك أي أعضاء في تلك المجموعة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: يُرفع إذا تم استدعاء هذه الطريقة بعد استدعاء طريقة detach. |

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
