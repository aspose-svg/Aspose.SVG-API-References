---
title: "Node.RemoveChild"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node RemoveChild メソッド。DOM から子ノードを削除し、削除されたノードを返します。"
type: docs
weight: 270
url: /ja/net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

DOM から子ノードを削除し、削除されたノードを返します。

注: 削除された子ノードへの参照が保持されている限り、メモリ上に残りますが、DOM の一部ではなくなります。コード内で後から再利用することも可能です。`RemoveChild` の戻り値が保存されず、他に参照が保持されていない場合、短時間で自動的にメモリから削除されます。

```csharp
public Node RemoveChild(Node child)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| child | Node | DOM から削除される子ノードである[`Node`](../)。 |

### 戻り値

[`CloneNode`](../clonenode/) とは異なり、戻り値はそれに関連付けられた[`EventListener`](../../../aspose.svg.dom.events/ieventlistener/) オブジェクトを保持します。

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
