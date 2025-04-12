---
title: Document.CreateNodeIterator
second_title: Aspose.SVG for .NET API Reference
description: Document CreateNodeIterator method. Create a new NodeIterator over the subtree rooted at the specified node
type: docs
weight: 900
url: /net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../node/)*) {#createnodeiterator}

Create a new NodeIterator over the subtree rooted at the specified node.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will be iterated together with its children. The iterator is initially positioned just before this node. The whatToShow flags and the filter, if any, are not considered when setting this position. The root must not be null. |

### Return Value

The newly created NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Raised if the specified root is null. |

### See Also

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long*) {#createnodeiterator_1}

Create a new NodeIterator over the subtree rooted at the specified node.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will be iterated together with its children. The iterator is initially positioned just before this node. The whatToShow flags and the filter, if any, are not considered when setting this position. The root must not be null. |
| whatToShow | Int64 | flag specifies which node types may appear in the logical view of the tree presented by the iterator. See the description of NodeFilter for the set of possible SHOW_ values.These flags can be combined using OR. |

### Return Value

The newly created NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Raised if the specified root is null. |

### See Also

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createnodeiterator_2}

Create a new NodeIterator over the subtree rooted at the specified node.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will be iterated together with its children. The iterator is initially positioned just before this node. The whatToShow flags and the filter, if any, are not considered when setting this position. The root must not be null. |
| whatToShow | Int64 | flag specifies which node types may appear in the logical view of the tree presented by the iterator. See the description of NodeFilter for the set of possible SHOW_ values.These flags can be combined using OR. |
| filter | INodeFilter | NodeFilter to be used with this TreeWalker, or null to indicate no filter. |

### Return Value

The newly created NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Raised if the specified root is null. |

### See Also

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
