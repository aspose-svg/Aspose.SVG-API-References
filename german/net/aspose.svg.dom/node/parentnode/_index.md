---
title: "Node.ParentNode"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Node ParentNode‑Eigenschaft. Gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück."
type: docs
weight: 130
url: /de/net/aspose.svg.dom/node/parentnode/
---
## Node.ParentNode property

Gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

Ein Node, der das übergeordnete Element des aktuellen Knotens ist. Der Elternknoten eines Elements ist ein [`Element`](../../element/)-Knoten, ein [`Document`](../../document/)-Knoten oder ein [`DocumentFragment`](../../documentfragment/)-Knoten.

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### Siehe auch

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
