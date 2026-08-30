---
title: "INodeIterator.NextNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "INodeIterator NextNode-metoden. Returnerar nästa nod i mängden och avancerar iteratorns position i mängden. Efter att en NodeIterator har skapats returnerar det första anropet till nextNode den första noden i mängden."
type: docs
weight: 40
url: /sv/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Returnerar nästa nod i uppsättningen och avancerar iteratorns position i uppsättningen. Efter att en NodeIterator har skapats returnerar det första anropet till nextNode() den första noden i uppsättningen.

```csharp
public Node NextNode()
```

### Returvärde

Den nästa noden i den itererade mängden, eller null om det inte finns fler medlemmar i den mängden.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Kastas om denna metod anropas efter att detach-metoden har anropats. |

### Se även

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
