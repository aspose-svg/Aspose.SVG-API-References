---
title: "Node.ReplaceChild"
second_title: "Aspose.SVG for .NET API 参考"
description: "Node ReplaceChild 方法。将子节点 oldChild 替换为 newChild，并在子节点列表中返回 oldChild 节点。如果 newChild 是 DocumentFragment 对象，则 oldChild 将被该 DocumentFragment 的所有子节点替换，这些子节点按相同顺序插入。如果 newChild 已经在树中，则首先将其移除。"
type: docs
weight: 280
url: /zh/net/aspose.svg.dom/node/replacechild/
---
## Node.ReplaceChild method

在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是 DocumentFragment 对象，oldChild 将被 DocumentFragment 的所有子节点替换，这些子节点按相同顺序插入。如果 newChild 已经在树中，则会先将其移除。

```csharp
public Node ReplaceChild(Node node, Node child)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | Node | 新的节点。 |
| child | Node | 旧子节点。 |

### 返回值

返回节点

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
