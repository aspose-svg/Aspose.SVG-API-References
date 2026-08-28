---
title: "INodeIterator.PreviousNode"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "INodeIterator PreviousNode メソッド。セット内の前のノードを返し、NodeIterator の位置をセット内で後方に移動させます。"
type: docs
weight: 50
url: /ja/net/aspose.svg.dom.traversal/inodeiterator/previousnode/
---
## INodeIterator.PreviousNode method

セット内の前のノードを返し、NodeIterator の位置をセット内で後方に移動させます。

```csharp
public Node PreviousNode()
```

### 戻り値

反復中のセット内の前のノード、またはそのセットにメンバーがもう無い場合は null。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: detach メソッドが呼び出された後にこのメソッドが呼び出された場合に発生します。 |

### 参照

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
