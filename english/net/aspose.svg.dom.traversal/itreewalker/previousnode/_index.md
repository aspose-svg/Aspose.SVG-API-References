---
title: ITreeWalker.PreviousNode
second_title: Aspose.SVG for .NET API Reference
description: ITreeWalker method. Moves the TreeWalker to the previous visible node in document order relative to the current node and returns the new node. If the current node has no previous node or if the search for previousNode attempts to step upward from the TreeWalkers root node returns null and retains the current node
type: docs
weight: 70
url: /net/aspose.svg.dom.traversal/itreewalker/previousnode/
---
## ITreeWalker.PreviousNode method

Moves the TreeWalker to the previous visible node in document order relative to the current node, and returns the new node. If the current node has no previous node, or if the search for previousNode attempts to step upward from the TreeWalker's root node, returns null, and retains the current node.

```csharp
public Node PreviousNode()
```

### Return Value

The new node, or null if the current node has no previous node in the TreeWalker's logical view.

### See Also

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
