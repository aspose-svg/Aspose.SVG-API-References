---
title: "ITreeWalker.PreviousNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "ITreeWalker PreviousNode-metod. Flyttar TreeWalker till den föregående synliga noden i dokumentordning relativt till den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har en föregående nod eller om sökningen efter previousNode försöker gå uppåt från TreeWalkers rot-nod returneras null och den aktuella noden behålls."
type: docs
weight: 70
url: /sv/net/aspose.svg.dom.traversal/itreewalker/previousnode/
---
## ITreeWalker.PreviousNode method

Flyttar TreeWalker till föregående synliga nod i dokumentordning relativt den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har någon föregående nod, eller om sökningen efter previousNode försöker gå uppåt från TreeWalkers rotnod, returneras null och den aktuella noden behålls.

```csharp
public Node PreviousNode()
```

### Returvärde

Den nya noden, eller null om den aktuella noden inte har en föregående nod i TreeWalkers logiska vy.

### Se även

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
