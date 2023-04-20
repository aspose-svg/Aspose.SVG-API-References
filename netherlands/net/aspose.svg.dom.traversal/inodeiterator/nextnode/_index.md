---
title: INodeIterator.NextNode
second_title: Aspose.SVG voor .NET API-referentie
description: INodeIterator methode. Retourneert het volgende knooppunt in de set en verhoogt de positie van de iterator in de set. Nadat een NodeIterator is gemaakt retourneert de eerste aanroep van nextNode het eerste knooppunt in de set.
type: docs
weight: 40
url: /nl/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Retourneert het volgende knooppunt in de set en verhoogt de positie van de iterator in de set. Nadat een NodeIterator is gemaakt, retourneert de eerste aanroep van nextNode() het eerste knooppunt in de set.

```csharp
public Node NextNode()
```

### Winstwaarde

Het volgende knooppunt in de set dat wordt herhaald, or null als er geen leden meer in die set zijn.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Verhoogd als deze methode wordt aangeroepen nadat de methode detach is aangeroepen. |

### Zie ook

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* naamruimte [Aspose.Svg.Dom.Traversal](../../inodeiterator/)
* montage [Aspose.SVG](../../../)


