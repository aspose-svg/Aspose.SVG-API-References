---
title: "Node.ParentNode"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство Node ParentNode. Возвращает родителя указанного узла в дереве DOM."
type: docs
weight: 130
url: /ru/net/aspose.svg.dom/node/parentnode/
---
## Node.ParentNode property

Возвращает родителя указанного узла в дереве DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

Узел, являющийся родителем текущего узла. Родителем элемента может быть узел [`Element`](../../element/), узел [`Document`](../../document/) или узел [`DocumentFragment`](../../documentfragment/).

## Замечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### См. также

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
