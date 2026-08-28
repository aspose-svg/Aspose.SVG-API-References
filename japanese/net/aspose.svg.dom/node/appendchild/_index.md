---
title: "Node.AppendChild"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node AppendChild メソッド。指定された親ノードの子リストの末尾にノードを追加します。与えられた child がドキュメント内の既存ノードへの参照である場合、AppendChild はそのノードを現在の位置から新しい位置へ移動させます。別のノードに追加する前に親ノードから削除する必要はありません。"
type: docs
weight: 170
url: /ja/net/aspose.svg.dom/node/appendchild/
---
## Node.AppendChild method

指定された親ノードの子リストの末尾にノードを追加します。与えられた child がドキュメント内の既存ノードへの参照である場合、`AppendChild` はそのノードを現在の位置から新しい位置へ移動させます（別のノードに追加する前に親ノードから削除する必要はありません）。

これは、ノードが文書内の複数の場所に同時に存在できないことを意味します。そのため、ノードに既に親がある場合、まずそのノードは削除され、次に新しい位置に追加されます。[`CloneNode`](../clonenode/) メソッドを使用すると、ノードを新しい親の下に追加する前にコピーを作成できます。[`CloneNode`](../clonenode/) で作成されたコピーは自動的に同期されません。

```csharp
public Node AppendChild(Node node)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | ノード | 指定された親ノード（通常は要素）に追加するノードです。 |

### 戻り値

追加された子ノードである Node です。ただし、child が [`DocumentFragment`](../../documentfragment/) の場合は、空の [`DocumentFragment`](../../documentfragment/) が返されます。

### 例外

| 例外 | 条件 |
| --- | --- |
| DOMException | DOM ツリーの制約が違反したときにスローされます。 |

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
