---
title: "Node.ParentNode"
second_title: "Aspose.SVG for .NET API 参考"
description: "Node ParentNode 属性。返回 DOM 树中指定节点的父节点"
type: docs
weight: 130
url: /zh/net/aspose.svg.dom/node/parentnode/
---
## Node.ParentNode property

返回 DOM 树中指定节点的父节点。

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

一个作为当前节点父节点的 Node。元素的父节点可以是 [`Element`](../../element/) 节点、[`Document`](../../document/) 节点或 [`DocumentFragment`](../../documentfragment/) 节点。

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
