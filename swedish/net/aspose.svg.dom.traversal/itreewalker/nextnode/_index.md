---
title: "ITreeWalker.NextNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "ITreeWalker NextNode-metod. Flyttar TreeWalker till nästa synliga nod i dokumentordning relativt till den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har en nästa nod eller om sökningen efter nextNode försöker gå uppåt från TreeWalkers rot-nod returneras null och den aktuella noden behålls."
type: docs
weight: 40
url: /sv/net/aspose.svg.dom.traversal/itreewalker/nextnode/
---
## ITreeWalker.NextNode method

Flyttar TreeWalker till nästa synliga nod i dokumentordning relativt den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har någon nästa nod, eller om sökningen efter nextNode försöker gå uppåt från TreeWalkers rotnod, returneras null och den aktuella noden behålls.

```csharp
public Node NextNode()
```

### Returvärde

Den nya noden, eller null om den aktuella noden inte har en nästa nod i TreeWalkers logiska vy.

### Se även

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
