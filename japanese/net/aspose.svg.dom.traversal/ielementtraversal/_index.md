---
title: Interface IElementTraversal
second_title: Aspose.SVG for .NET API リファレンス
description: Aspose.Svg.Dom.Traversal.IElementTraversal インターフェース. ElementTraversal インターフェイスは作成者がドキュメント内の要素間を簡単にナビゲートできるようにする読み取り専用属性のセットです Element Traversal の適合する実装ではElement を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装する必要があります
type: docs
weight: 1230
url: /ja/net/aspose.svg.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal インターフェイスは、作成者がドキュメント内の要素間を簡単にナビゲートできるようにする読み取り専用属性のセットです。 Element Traversal の適合する実装では、Element を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装する必要があります。

```csharp
public interface IElementTraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom.traversal/ielementtraversal/childelementcount/) { get; } | この要素の子である要素ノードの現在の数を返します。この要素に nodeType 1. の子ノードがない場合は 0 |
| [FirstElementChild](../../aspose.svg.dom.traversal/ielementtraversal/firstelementchild/) { get; } | この要素の最初の子要素ノードを返します。この要素に子要素がない場合は null. |
| [LastElementChild](../../aspose.svg.dom.traversal/ielementtraversal/lastelementchild/) { get; } | この要素の最後の子要素ノードを返します。この要素に子要素がない場合は null. |
| [NextElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | この要素の次の兄弟要素ノードを返します。この要素に、ドキュメント ツリーでこの要素の後に続く要素兄弟ノードがない場合は null. |
| [PreviousElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | この要素の前の兄弟要素ノードを返します。この要素に、ドキュメント ツリー内でこの要素の前にある要素の兄弟ノードがない場合は null. |

### 関連項目

* 名前空間 [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* 組み立て [Aspose.SVG](../../)


