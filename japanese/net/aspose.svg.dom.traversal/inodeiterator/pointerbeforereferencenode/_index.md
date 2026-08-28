---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "INodeIterator PointerBeforeReferenceNode property. このフラグの値は、エンティティ参照ノードの子がイテレータに対して可視かどうかを決定します。false の場合、これらとその子孫は除外されます。この除外は whatToShow とフィルタよりも優先されます。また、現在 NodeIterators が個々のノードをスキップするのではなく、完全なサブツリーを除外できる唯一の状況です。エンティティ参照が展開され、エンティティ参照ノード自体を表示しないドキュメントビューを作成するには、whatToShow フラグでエンティティ参照ノードを非表示にし、イテレータ作成時に expandEntityReferences を true に設定します。エンティティ参照ノードはあるがエンティティ展開を行わないビューを作成するには、whatToShow フラグでエンティティ参照ノードを表示し、expandEntityReferences を false に設定します。"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

このフラグの値は、エンティティ参照ノードの子がイテレータに対して表示可能かどうかを決定します。false の場合、これらとその子孫は除外されます。この除外は whatToShow とフィルタよりも優先されます。また、現在これは NodeIterators が個々のノードをスキップするのではなく、完全なサブツリーを除外できる唯一の状況です。エンティティ参照が展開された状態でエンティティ参照ノード自体を公開しないドキュメントのビューを作成するには、whatToShow フラグでエンティティ参照ノードを非表示にし、イテレータ作成時に expandEntityReferences を true に設定します。エンティティ参照ノードはあるがエンティティ展開を行わないビューを作成するには、whatToShow フラグでエンティティ参照ノードを表示し、expandEntityReferences を false に設定します。

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` なら [expand entity references]、それ以外は `false`。

### 参照

* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
