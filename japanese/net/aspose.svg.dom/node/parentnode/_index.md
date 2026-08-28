---
title: "Node.ParentNode"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node ParentNode プロパティ。指定されたノードの DOM ツリー上の親ノードを返します。"
type: docs
weight: 130
url: /ja/net/aspose.svg.dom/node/parentnode/
---
## Node.ParentNode property

DOM ツリー内で指定されたノードの親を返します。

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

現在のノードの親である Node。要素の親は[`Element`](../../element/) ノード、[`Document`](../../document/) ノード、または[`DocumentFragment`](../../documentfragment/) ノードのいずれかです。

## 備考

参照:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
