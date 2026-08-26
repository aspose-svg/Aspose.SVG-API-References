---
title: "INodeIterator.NextNode"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "INodeIterator NextNode-Methode. Gibt den nächsten Knoten im Satz zurück und bewegt die Position des Iterators im Satz vorwärts. Nachdem ein NodeIterator erstellt wurde, liefert der erste Aufruf von nextNode den ersten Knoten im Satz."
type: docs
weight: 40
url: /de/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Gibt den nächsten Knoten in der Menge zurück und verschiebt die Position des Iterators in der Menge nach vorne. Nachdem ein NodeIterator erstellt wurde, liefert der erste Aufruf von nextNode() den ersten Knoten in der Menge.

```csharp
public Node NextNode()
```

### Rückgabewert

Der nächste Knoten im iterierten Satz, oder null, wenn keine weiteren Elemente in diesem Satz vorhanden sind.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Wird ausgelöst, wenn diese Methode nach dem Aufruf von detach aufgerufen wird. |

### Siehe auch

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
