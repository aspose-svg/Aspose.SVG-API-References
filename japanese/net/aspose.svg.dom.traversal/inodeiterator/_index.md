---
title: "INodeIterator インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Traversal.INodeIterator インターフェイス。イテレータは、NodeList のノード集合、特定のノードが支配するドキュメントサブツリー、クエリ結果、またはその他のノード集合など、一連のノードを順に処理するために使用されます。イテレートされるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は、ドキュメント順走査のための単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは、DocumentTraversal の createNodeIterator を呼び出すことで作成されます。"
type: docs
weight: 3250
url: /ja/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

イテレータはノードの集合を順に処理するために使用されます。例えば NodeList のノード集合、特定の Node が管理する文書サブツリー、クエリの結果、またはその他の任意のノード集合です。イテレートされるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は文書順走査用の単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal .createNodeIterator() を呼び出すことで作成されます。

また、[Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) も参照してください。@since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | このフラグの値は、エンティティ参照ノードの子がイテレータに対して表示可能かどうかを決定します。false の場合、これらとその子孫は除外されます。この除外は whatToShow とフィルタよりも優先されます。また、現在これは NodeIterators が個々のノードをスキップするのではなく、完全なサブツリーを除外できる唯一の状況です。エンティティ参照が展開された状態でエンティティ参照ノード自体を公開しないドキュメントのビューを作成するには、whatToShow フラグでエンティティ参照ノードを非表示にし、イテレータ作成時に expandEntityReferences を true に設定します。エンティティ参照ノードはあるがエンティティ展開を行わないビューを作成するには、whatToShow フラグでエンティティ参照ノードを表示し、expandEntityReferences を false に設定します。 |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | 現在の参照ノードです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | NodeIterator を反復したセットから切り離し、計算リソースを解放し、イテレータを INVALID 状態にします。detach が呼び出された後、nextNode または previousNode の呼び出しは例外 INVALID_STATE_ERR を発生させます。 |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | セット内の次のノードを返し、イテレータの位置をセット内で進めます。NodeIterator が作成された後、最初に nextNode() を呼び出すとセット内の最初のノードが返されます。 |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | セット内の前のノードを返し、NodeIterator の位置をセット内で後方に移動させます。 |

### 参照

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
