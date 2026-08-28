---
title: "Node.InsertBefore"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node InsertBefore メソッド。指定された子ノード child の前にノードを挿入します。child が null の場合、ノードは子リストの末尾に挿入されます。child が DocumentFragment オブジェクトの場合、そのすべての子が同じ順序で child の前に挿入されます。子ノードがすでにツリー内にある場合、まずそれが削除されます。"
type: docs
weight: 200
url: /ja/net/aspose.svg.dom/node/insertbefore/
---
## Node.InsertBefore method

既存の子ノード child の前にノードを挿入します。child が null の場合、子リストの末尾にノードを挿入します。child が DocumentFragment オブジェクトの場合、そのすべての子が同じ順序で child の前に挿入されます。子がすでにツリーに存在する場合、まず削除されます。

```csharp
public Node InsertBefore(Node node, Node child)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | ノード | 新しい子ノードです。 |
| child | ノード | 参照子ノードです。 |

### 戻り値

挿入されたノードを返します

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
