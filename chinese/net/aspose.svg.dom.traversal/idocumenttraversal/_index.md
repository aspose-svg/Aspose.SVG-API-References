---
title: "IDocumentTraversal 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Traversal.IDocumentTraversal 接口。DocumentTraversal 包含创建迭代器和树遍历器的方法，用于以文档顺序深度优先前序遍历节点及其子节点，这等同于文档文本表示中开始标签出现的顺序。在支持 Traversal 功能的 DOM 中，DocumentTraversal 将由实现 Document 接口的同一对象实现。"
type: docs
weight: 3220
url: /zh/net/aspose.svg.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal 包含用于创建迭代器和树遍历器，以按文档顺序（深度优先、先序遍历，即与文档文本表示中起始标签出现顺序相同）遍历节点及其子节点的方法。在支持 Traversal 特性的 DOM 中，DocumentTraversal 将由实现 Document 接口的同一对象实现。

另请参阅 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。@since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(*[Node](../../aspose.svg.dom/node/)*) | 在指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(*[Node](../../aspose.svg.dom/node/), long*) | 在指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | 在指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(*[Node](../../aspose.svg.dom/node/)*) | 在指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(*[Node](../../aspose.svg.dom/node/), long*) | 在指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | 在指定节点为根的子树上创建一个新的 TreeWalker。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
