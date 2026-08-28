---
title: "Node.ReplaceChild"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node ReplaceChild メソッド。子ノード oldChild を newChild に置き換え、子リスト内で oldChild ノードを返します。newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、最初に削除されます。"
type: docs
weight: 280
url: /ja/net/aspose.svg.dom/node/replacechild/
---
## Node.ReplaceChild method

子ノード oldChild を newChild に置き換え、子リスト内で置換し、oldChild ノードを返します。newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まずそれが削除されます。

```csharp
public Node ReplaceChild(Node node, Node child)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | ノード | 新しいノード。 |
| child | ノード | 古い子ノード。 |

### 戻り値

ノードを返します。

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
