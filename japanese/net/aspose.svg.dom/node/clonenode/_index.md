---
title: "Node.CloneNode"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node CloneNode メソッド。呼び出されたノードの複製を返します"
type: docs
weight: 180
url: /ja/net/aspose.svg.dom/node/clonenode/
---
## CloneNode() {#clonenode}

このメソッドが呼び出されたノードの複製を返します。

ノードをクローンすると、その属性と属性値がすべてコピーされ、固有の（インライン）リスナーも含まれます。[`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) を使用して追加されたイベントリスナーや、要素プロパティに割り当てられたリスナー（例: node.onclick = someFunction） はコピーされません。さらに、HTMLCanvasElement 要素の場合、描画された画像はコピーされません。

```csharp
public Node CloneNode()
```

### 戻り値

新しくクローンされた [`Node`](../) です。クローンされたノードは親を持たず、ドキュメントの一部ではありません。ドキュメントの一部である別のノードに、[`AppendChild`](../appendchild/) などのメソッドで追加されるまでです。

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CloneNode(*bool*) {#clonenode_1}

このメソッドが呼び出されたノードの複製を返します。そのパラメータはノードに含まれるサブツリーもクローンするかどうかを制御します。

ノードをクローンすると、その属性と属性値がすべてコピーされ、固有の（インライン）リスナーも含まれます。[`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) を使用して追加されたイベントリスナーや、要素プロパティに割り当てられたリスナー（例: node.onclick = someFunction） はコピーされません。さらに、HTMLCanvasElement 要素の場合、描画された画像はコピーされません。

```csharp
public Node CloneNode(bool deep)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | Boolean | true の場合、ノードとその全サブツリーが、子 [`Text`](../../text/) ノードに含まれる可能性のあるテキストも含めてコピーされます。 |

### 戻り値

新しくクローンされた [`Node`](../) です。クローンされたノードは親を持たず、ドキュメントの一部ではありません。ドキュメントの一部である別のノードに、[`AppendChild`](../appendchild/) などのメソッドで追加されるまでです。

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
