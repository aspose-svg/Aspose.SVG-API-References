---
title: "Node.ParentNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "خاصية Node ParentNode. تُرجع الأب للعقدة المحددة في شجرة DOM."
type: docs
weight: 130
url: /ar/net/aspose.svg.dom/node/parentnode/
---
## Node.ParentNode property

يعيد أب العقدة المحددة في شجرة DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

عقدة Node هي الأب للعقدة الحالية. أب العنصر هو عقدة [`Element`](../../element/)، أو عقدة [`Document`](../../document/)، أو عقدة [`DocumentFragment`](../../documentfragment/).

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
