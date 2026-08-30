---
title: "Node.ParentNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "Node ParentNode‑egenskap. Returnerar föräldern till den angivna noden i DOM‑trädet"
type: docs
weight: 130
url: /sv/net/aspose.svg.dom/node/parentnode/
---
## Node.ParentNode property

Returnerar föräldern till den angivna noden i DOM-trädet.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

En Node som är föräldern till den aktuella noden. Föräldern till ett element är ett [`Element`](../../element/)‑nod, ett [`Document`](../../document/)‑nod eller ett [`DocumentFragment`](../../documentfragment/)‑nod.

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### Se även

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
