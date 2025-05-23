---
title: INodeIterator Interface
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Dom.Traversal.INodeIterator interface. Iterators are used to step through a set of nodes e.g. the set of nodes in a NodeList the document subtree governed by a particular Node the results of a query or any other set of nodes. The set of nodes to be iterated is determined by the implementation of the NodeIterator. DOM Level 2 specifies a single NodeIterator implementation for document-order traversal of a document subtree. Instances of these iterators are created by calling DocumentTraversal .createNodeIterator
type: docs
weight: 3250
url: /net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iterators are used to step through a set of nodes, e.g. the set of nodes in a NodeList, the document subtree governed by a particular Node, the results of a query, or any other set of nodes. The set of nodes to be iterated is determined by the implementation of the NodeIterator. DOM Level 2 specifies a single NodeIterator implementation for document-order traversal of a document subtree. Instances of these iterators are created by calling DocumentTraversal .createNodeIterator().

See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## Properties

| Name | Description |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | The value of this flag determines whether the children of entity reference nodes are visible to the iterator. If false, they and their descendants will be rejected. Note that this rejection takes precedence over whatToShow and the filter. Also note that this is currently the only situation where NodeIterators may reject a complete subtree rather than skipping individual nodes. To produce a view of the document that has entity references expanded and does not expose the entity reference node itself, use the whatToShow flags to hide the entity reference node and set expandEntityReferences to true when creating the iterator. To produce a view of the document that has entity reference nodes but no entity expansion, use the whatToShow flags to show the entity reference node and set expandEntityReferences to false. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | The current reference node. |

## Methods

| Name | Description |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | Detaches the NodeIterator from the set which it iterated over, releasing any computational resources and placing the iterator in the INVALID state. After detach has been invoked, calls to nextNode or previousNode will raise the exception INVALID_STATE_ERR. |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | Returns the next node in the set and advances the position of the iterator in the set. After a NodeIterator is created, the first call to nextNode() returns the first node in the set. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | Returns the previous node in the set and moves the position of the NodeIterator backwards in the set. |

### See Also

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
