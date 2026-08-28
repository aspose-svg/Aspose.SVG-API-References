---
title: "INodeIterator.NextNode"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "INodeIterator NextNode メソッド。セット内の次のノードを返し、イテレータの位置をセット内で進めます。NodeIterator が作成された後、最初の nextNode 呼び出しはセット内の最初のノードを返します。"
type: docs
weight: 40
url: /ja/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

セット内の次のノードを返し、イテレータの位置をセット内で進めます。NodeIterator が作成された後、最初に nextNode() を呼び出すとセット内の最初のノードが返されます。

```csharp
public Node NextNode()
```

### 戻り値

反復中のセット内の次のノード、またはそのセットにメンバーがもう無い場合は null。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: detach メソッドが呼び出された後にこのメソッドが呼び出された場合に発生します。 |

### 参照

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
