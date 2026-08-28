---
title: "INodeFilter.AcceptNode"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "INodeFilter AcceptNode メソッド。指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出され、通常はユーザーコードから直接呼び出されません。ただし、同じフィルタを使用して独自のアプリケーションロジックを導く場合は呼び出すことも可能です"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出され、通常はユーザーコードから直接呼び出されません。（同じフィルタを使用して独自のアプリケーションロジックを導く場合は、呼び出すことも可能です。）

```csharp
public short AcceptNode(Node n)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| n | ノード | フィルタを通過するかどうかを確認するノード。 |

### 戻り値

上記で定義されたように、ノードが受け入れられるか、拒否されるか、スキップされるかを決定する定数。

### 参照

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
