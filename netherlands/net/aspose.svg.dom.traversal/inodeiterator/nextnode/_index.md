---
title: "INodeIterator.NextNode"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "INodeIterator NextNode-methode. Retourneert de volgende node in de verzameling en verschuift de positie van de iterator in de verzameling vooruit. Nadat een NodeIterator is aangemaakt, geeft de eerste aanroep van nextNode de eerste node in de verzameling terug."
type: docs
weight: 40
url: /nl/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Retourneert het volgende knooppunt in de set en verplaatst de positie van de iterator in de set vooruit. Nadat een NodeIterator is aangemaakt, retourneert de eerste oproep naar nextNode() het eerste knooppunt in de set.

```csharp
public Node NextNode()
```

### Retourwaarde

De volgende Node in de verzameling die wordt geïtereerd, of null als er geen leden meer in die verzameling zijn.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Opgeworpen als deze methode wordt aangeroepen nadat de detach-methode is uitgevoerd. |

### Zie ook

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
