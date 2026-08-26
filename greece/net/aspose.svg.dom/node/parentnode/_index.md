---
title: "Node.ParentNode"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Ιδιότητα Node.ParentNode. Επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM."
type: docs
weight: 130
url: /el/net/aspose.svg.dom/node/parentnode/
---
## Node.ParentNode property

Επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

Ένας Node που είναι ο γονέας του τρέχοντος κόμβου. Ο γονέας ενός στοιχείου είναι ένας κόμβος [`Element`](../../element/), ένας κόμβος [`Document`](../../document/) ή ένας κόμβος [`DocumentFragment`](../../documentfragment/).

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
