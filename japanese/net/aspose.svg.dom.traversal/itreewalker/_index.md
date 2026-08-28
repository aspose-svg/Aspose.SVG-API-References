---
title: "ITreeWalker インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Traversal.ITreeWalker インターフェイス。TreeWalker オブジェクトは、whatToShow フラグと（存在する場合の）フィルタで定義されたドキュメントのビューを使用して、ドキュメントツリーまたはサブツリーをナビゲートするために使用されます。TreeWalker を使用してナビゲーションを行うすべての関数は、TreeWalker が定義する任意のビューを自動的にサポートします。"
type: docs
weight: 3270
url: /ja/net/aspose.svg.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker オブジェクトは、whatToShow フラグとフィルタ（存在する場合）で定義された文書のビューを使用して、文書ツリーまたはサブツリーをナビゲートするために使用されます。TreeWalker を使用してナビゲーションを行うすべての関数は、TreeWalker が定義する任意のビューを自動的にサポートします。

サブツリーの論理ビューからノードを除外すると、完全でフィルタなしのドキュメント内の同じサブツリーとは実質的に異なる構造になることがあります。TreeWalker ビューで兄弟関係にあるノードは、元のビューでは異なる、遠く離れたノードの子になることがあります。例えば、テキストノードとドキュメントのルートノード以外のすべてのノードをスキップする NodeFilter を考えてみましょう。その結果得られる論理ビューでは、すべてのテキストノードが兄弟となり、ルートノードの直接の子として表示され、元のドキュメントの構造がどれだけ深くネストされていても同様です。

また、[Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) も参照してください。@since DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CurrentNode](../../aspose.svg.dom.traversal/itreewalker/currentnode/) { get; set; } | TreeWalker が現在位置しているノードです。DOM ツリーの変更により、現在のノードが TreeWalker に関連付けられたフィルタによってもはや受け入れられなくなることがあります。currentNode は、ルートノードで指定されたサブツリー内にあるかどうか、またはフィルタや whatToShow フラグで受け入れられるかどうかに関係なく、任意のノードに明示的に設定することもできます。さらに、currentNode が現在のビューの一部でなくても、要求された方向のフィルタを適用して走査が続行されます。走査が不可能な場合、currentNode は変更されません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FirstChild](../../aspose.svg.dom.traversal/itreewalker/firstchild/)() | TreeWalker を現在のノードの最初の表示子ノードに移動し、新しいノードを返します。現在のノードに表示子ノードがない場合は null を返し、現在のノードを保持します。 |
| [LastChild](../../aspose.svg.dom.traversal/itreewalker/lastchild/)() | TreeWalker を現在のノードの最後の表示子ノードに移動し、新しいノードを返します。現在のノードに表示子ノードがない場合は null を返し、現在のノードを保持します。 |
| [NextNode](../../aspose.svg.dom.traversal/itreewalker/nextnode/)() | TreeWalker を現在のノードに対して文書順で次の表示可能なノードへ移動し、新しいノードを返します。現在のノードに次のノードがない場合、または nextNode の検索が TreeWalker のルートノードから上方へ移動しようとした場合は null を返し、現在のノードを保持します。 |
| [NextSibling](../../aspose.svg.dom.traversal/itreewalker/nextsibling/)() | TreeWalker を現在のノードの次の兄弟ノードへ移動し、新しいノードを返します。現在のノードに表示可能な次の兄弟ノードがない場合は null を返し、現在のノードを保持します。 |
| [ParentNode](../../aspose.svg.dom.traversal/itreewalker/parentnode/)() | 現在のノードの最も近い表示可能な祖先ノードへ移動し、そのノードを返します。parentNode の検索が TreeWalker のルートノードから上方へ移動しようとした場合、または表示可能な祖先ノードが見つからなかった場合は、現在の位置を保持し null を返します。 |
| [PreviousNode](../../aspose.svg.dom.traversal/itreewalker/previousnode/)() | TreeWalker を現在のノードに対して文書順で前の表示可能なノードへ移動し、新しいノードを返します。現在のノードに前のノードがない場合、または previousNode の検索が TreeWalker のルートノードから上方へ移動しようとした場合は null を返し、現在のノードを保持します。 |
| [PreviousSibling](../../aspose.svg.dom.traversal/itreewalker/previoussibling/)() | TreeWalker を現在のノードの前の兄弟ノードへ移動し、新しいノードを返します。現在のノードに表示可能な前の兄弟ノードがない場合は null を返し、現在のノードを保持します。 |

### 参照

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
