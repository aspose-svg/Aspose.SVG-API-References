---
title: "IDocumentTraversal インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Traversal.IDocumentTraversal インターフェイス。DocumentTraversal には、イテレータやツリーワーカーを作成し、ノードとその子を文書順の深さ優先事前順序で走査するメソッドが含まれます。これは、ドキュメントのテキスト表現で開始タグが現れる順序に相当します。Traversal 機能をサポートする DOM では、DocumentTraversal は Document インターフェイスを実装するオブジェクトと同じオブジェクトで実装されます。"
type: docs
weight: 3220
url: /ja/net/aspose.svg.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal には、ノードとその子を文書順（深さ優先・先行順走査、つまり文書のテキスト表現における開始タグの出現順と同等）に走査するイテレータやツリーワーカーを作成するメソッドが含まれています。Traversal 機能をサポートする DOM では、DocumentTraversal は Document インターフェイスを実装するオブジェクトと同じオブジェクトによって実装されます。

また、[Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) も参照してください。@since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(*[Node](../../aspose.svg.dom/node/)*) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(*[Node](../../aspose.svg.dom/node/), long*) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(*[Node](../../aspose.svg.dom/node/)*) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(*[Node](../../aspose.svg.dom/node/), long*) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |

### 参照

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
