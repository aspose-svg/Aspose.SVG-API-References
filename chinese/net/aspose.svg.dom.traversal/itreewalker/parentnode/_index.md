---
title: "ITreeWalker.ParentNode"
second_title: "Aspose.SVG for .NET API 参考"
description: "ITreeWalker ParentNode 方法。移动到并返回当前节点最近的可见祖先节点。如果对 parentNode 的搜索尝试从 TreeWalker 的根节点向上移动，或未能找到可见的祖先节点，则该方法保留当前位置信息并返回 null。"
type: docs
weight: 60
url: /zh/net/aspose.svg.dom.traversal/itreewalker/parentnode/
---
## ITreeWalker.ParentNode method

移动并返回当前节点最近的可见祖先节点。如果搜索 parentNode 时尝试从 TreeWalker 的根节点向上移动，或未能找到可见的祖先节点，则此方法保持当前定位并返回 null。

```csharp
public Node ParentNode()
```

### 返回值

新的父节点；如果在 TreeWalker 的逻辑视图中当前节点没有父节点，则为 null。

### 另请参阅

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
