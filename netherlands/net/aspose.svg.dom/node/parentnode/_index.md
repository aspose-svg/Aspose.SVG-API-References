---
title: "Node.ParentNode"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Node ParentNode‑eigenschap. Retourneert de ouder van de opgegeven knoop in de DOM‑boom."
type: docs
weight: 130
url: /nl/net/aspose.svg.dom/node/parentnode/
---
## Node.ParentNode property

Retourneert de ouder van het opgegeven knooppunt in de DOM-boom.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

Een Node die de ouder is van de huidige knoop. De ouder van een element is een [`Element`](../../element/)‑knoop, een [`Document`](../../document/)‑knoop, of een [`DocumentFragment`](../../documentfragment/)‑knoop.

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### Zie ook

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
