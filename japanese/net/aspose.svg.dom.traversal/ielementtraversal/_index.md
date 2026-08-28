---
title: "IElementTraversal インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Traversal.IElementTraversal インターフェイス。ElementTraversal インターフェイスは、著者がドキュメント内の要素間を簡単にナビゲートできるようにする読み取り専用属性の集合です。Element Traversal の準拠実装では、Element を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装しなければなりません。"
type: docs
weight: 3230
url: /ja/net/aspose.svg.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal インターフェイスは、著者が文書内の要素間を簡単に移動できるようにする読み取り専用属性の集合です。Element Traversal の準拠実装では、Element を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装しなければなりません。

```csharp
public interface IElementTraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom.traversal/ielementtraversal/childelementcount/) { get; } | この要素の子である要素ノードの現在の数を返します。nodeType が 1 の子ノードがない場合は 0 を返します。 |
| [FirstElementChild](../../aspose.svg.dom.traversal/ielementtraversal/firstelementchild/) { get; } | この要素の最初の子要素ノードを返します。子要素がない場合は null。 |
| [LastElementChild](../../aspose.svg.dom.traversal/ielementtraversal/lastelementchild/) { get; } | この要素の最後の子要素ノードを返します。子要素がない場合は null。 |
| [NextElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | この要素の次の兄弟要素ノードを返します。文書ツリー内でこの要素の後に来る要素の兄弟ノードがない場合は null。 |
| [PreviousElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | この要素の前の兄弟要素ノードを返します。文書ツリー内でこの要素の前に来る要素の兄弟ノードがない場合は null。 |

### 参照

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
